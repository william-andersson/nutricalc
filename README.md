# NutriCalc
Calculate nutritional values for product labeling. Pick the ingredients and amount used according to recepie and optionaly save the product to the database for later use.

![Screenshot](https://github.com/william-andersson/nutricalc/blob/main/main_window.png)<br>
Test using the run-script. It initiates a virtual environment and starts the application.<br>
Linux: `chmod 755 run.sh` && `./run.sh`<br>
Windows: `run.bat`<br>

> [!NOTE]
> :blue_square: THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT ANY WARRANTY.<br>
> :blue_square: This application is made to comply with EU regulations only.<br>
> :blue_square: All values except 'Fiber content' is required on labels.<br>
> :blue_square: Alcohol content is purpesly left out! (Alcohol content is also used to calculate calories, add it to the code if you need it in production.

## Manage the database
In this window you can remove products from the database by selecting the name and click 'remove'. You can also add products that do not need to be calculated e.g. bought finished products.

![Screenshot](https://github.com/william-andersson/nutricalc/blob/main/db_window.png)<br>

> [!NOTE]
> When adding bought products remember that 'Fiber content' is not required on labels BUT is used to correctly calculate calories, contact the producer if the label does not include fiber content.
