# Distance calculator in Google sheets
Distance calculator in google sheets
Just call the function "GOOGLEMAPS()" passing two arguments, start_address and end_address. Both arguments should be strings

If one of the arguments is a geolocation, pass it as a string using decimals, like so: "52.5088363,13.6357551"

## How to use this code

Apply it as a scrpit in a Google sheets. Go to Extensions > AppScript

<img width="679" alt="image" src="https://github.com/Bernardo-giff/distance_calculator_gs/assets/73885759/fac7358d-2758-4ab1-874c-7c42965aff7e">

Once you have done this, deploy the code and the function will be available in Google Sheets.

To call it, apply it in any cell by using the "=" sign. Such as: =GOOGLEMAPS(<cell_1>, <cell_2>). Cells 1 and 2 should be replaced by cells containing the start address and end address respectively

