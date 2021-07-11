# form-validator-project

This is a project from the "JavaScript Web Projects: 20 Projects to Build Your Portfolio" class on Udemy \(<https://www.udemy.com>\).

This project was started June 29, 2021 and completed July 10, 2021.

The objective of this project was to create a form validator using HTML5 input attributes and JavaScript to provide validation of input fields on a registration form. Feedback provided to the user included using patterns to enforce input formats, the *require* attribute to indicate required inputs, and success or error messages to provide feedback to the user.

This project was only tested in Firefox Developer Edition Version 90.0b12 \(64-bit\).

## Modifications and Enhancements

The following modifications and enhancements can be implemented in future versions to address or correct implementation issues or functionality:

- [ ] add a button to clear the form

    Currently, the form does not clear itself when the 'Submit' button is clicked.
    
- [ ] clear the form when the page is reloaded

    Reloading the page does not clear all of the input fields. Currently, when the page is reloaded, only the 'Create Password' and 'Confirm Password' fields are cleared and the message box is returned to it's original state.
    
## Lessons Learned

* Preventing default behavior for an event using Event.preventDefault\(\) when working with a form's submit event \(<https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault>\)

* Manipulating CSS properties in JavaScript \(see CSS Properties Reference <https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference>\)

    Example:
    
        password1El.style.borderColor = 'green';
        message.textContent = 'Successfully Registered!';
        
* The use of *display: flex* and *flex-direction: row | column* to control layout

* input attributes:

    * minlength | maxlength
    
    * type attribute \(<https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input>\)
    
    * required
    
    * placeholder
    
    * pattern \(<https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#htmlattrdefpattern>\)
    
    * title

## Resources and References

* [HTML Forms](https://www.w3schools.com/html/html_forms.asp)

* [\<input\>: The Input \(Form Input\) element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

* [Google Fonts](https://fonts.google.com/)

    * Original font: [Sen](https://fonts.google.com/specimen/Sen?query=sen)
    
    * Actual font: [Encode Sans SC](https://fonts.google.com/specimen/Encode+Sans+SC)

* [:valid pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:valid)

* [Password Validation regex pattern](https://regexr.com/3bfsi)

* [Constraint validation](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Constraint_validation)

* [Client-side form validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)

* [HTMLFormElement: submit event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/submit_event)

* [Form Validation Part 1: Constraint Validation in HTML](https://css-tricks.com/form-validation-part-1-constraint-validation-html/)

* [preventDefault() Event Method](https://www.w3schools.com/jsref/event_preventdefault.asp)
