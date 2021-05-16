# Calculate VAT

This package contains a function to calculate the price of a product with VAT

## Usage

```Javascript
var calculate_VAT=require("./calculatevat").calculate_VAT;
let calc=calculate_VAT(1524,11);
console.log("The VAT to pay is: "+calc.vat);
console.log("The total to pay already with the VAT included is: "+calc.total);

```