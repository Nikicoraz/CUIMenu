# Menu Utils
A simple library to create simple CUI menus that work using the arrow keys  

## Usage
At the top of your program write `using MenuCreator;`

then in your file, when you want to create the menu call the CreateMenu function in the MenuUtils class.
This function returns an index of the option which has been selected (indexes start at 0)  
ex.

```cs
int scelta = MenuUtils.CreateMenu(new string[] { "Salame", "Pesce", "Carne", "Ho finito i tipi di panini :(" }, "Che tipo di panino ti piace?");
switch(scelta)
{
	...
}
```
