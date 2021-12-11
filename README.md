### This is the 2.1.0 Release of the package , 2.1.1 has a lot of breaking changes 








## How to Use

Simply create a `IntlPhoneField` widget, and pass the required params:z

```dart
IntlPhoneField(
    decoration: InputDecoration(
        labelText: 'Phone Number',
        border: OutlineInputBorder(
            borderSide: BorderSide(),
        ),
    ),
    initialCountryCode: 'IN',
    onChanged: (phone) {
        print(phone.completeNumber);
    },
)
```

Use `initialCountryCode` to set an initial Country Code.
