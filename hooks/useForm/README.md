# useForm Hook

Example of use:

```

  //Random values, it could be whatever you want
  const initialFormValues = {
    name: <any_name>,
    age: <any_age>,
    email: <any_email>
  };

  const [ formValues, handleInputChange, reset ] = useForm(initialFormValues);

  - Form values: Values of the form (name, age and email in this case).

  - handleInputChange(inputTarget): Method to execute when one input is modified.

  - Reset: Method to call to reset form values to the default ones.

```
