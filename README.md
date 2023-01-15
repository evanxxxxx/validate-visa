# validate-visa
This program defines a function called validateVisaCard() that takes a card number as an argument. It then uses a regular expression to check whether the card number is a valid Visa card number.

The regular expression pattern i used in this program is:

Copy code
^4[0-9]{12}(?:[0-9]{3})?$
This pattern matches the following:

The card number must start with a 4 (^4).
The card number must have 12 digits after the first digit ([0-9]{12}).
The card number may have an optional group of 3 digits after the 12 digits (?:[0-9]{3})?).
The card number must end with the end of the string ($).
The program uses the test() method to check whether the card number matches the regular expression pattern. If it does, the function returns true, otherwise it returns false.
 
Note: This is just validation for visa cards,a similar pattern can be used for other cards like Mastercard, etc.
