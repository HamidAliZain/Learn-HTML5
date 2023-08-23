# Forms

Forms in HTML allow users to input and submit data it locally using various types of input fields. Here's how you can create a basic form using HTML. example is in the html file

# Inputs

In HTML, input elements are used to create various types of interactive form controls that allow users to input data. Input elements are an essential part of forms and allow users to submit data to be processed. Here are some common input types and how to use them:

## Text Input

This creates a single-line text input field where users can enter plain text.

```
<input type="text" name="username">
```

## Password Input

This creates a text input field where the entered text is masked (usually with asterisks) to hide sensitive information like passwords.

```
<input type="password" name="password">
```

## Email Input

This creates a text input field specifically designed for email addresses. Browsers usually provide validation for valid email formats.

```
<input type="email" name="email">
```

## Radio Input

Radio buttons are used when users need to select one option from a list of choices.

```
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```

## Checkboxes Input

Checkboxes allow users to select multiple options from a list.

```
<input type="checkbox" name="fruit" value="apple"> Apple
<input type="checkbox" name="fruit" value="banana"> Banana
<input type="checkbox" name="fruit" value="orange"> Orange
```

## Textarea Input

This creates a multi-line text input field for longer text input, such as comments or messages.

```
<textarea name="comments" rows="4" cols="50"></textarea>
```
