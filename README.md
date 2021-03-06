# Welcome to RC-Calc!

A self-hosted ~hopefully one day~ all-in-one calculator for FPV planes, multirotors and other autonomous or R/C flying stuff.

This project aim to group in one place the different tools I made on Excel spreadsheets, to share them in a more user-friendly way.

## What does it do now?
> :warning: This is currently an alpha version, expect some bugs and very limited features!

It is currently under the form of a self-hosted web server. It means that when you run the program, it looks like a normal website but nothing actually goes in and out of your computer.

For now, RC-Calc allows you to:
- Set the proper mV/A for you current sensor, in order to get an accurate power/energy draw reading in your OSD. Might be useful for sweets long-range flights!

## What's next?
I have some tools that just need to be included in this program and will give the following features:
- A flight time tracking tool: log your flight times and distances so you can quickly tell if this new battery, propeller or any other equipment actually gives you more performance than usual.
- A battery configurator: to help you building the ultimate li-ion pack. Choose your cells, series and parallel configuration and you will get the weight, price, voltage, capacity of the pack to determine what suits best your needs!

I also have some other tools but I don't really know if they should be included since they are really specific and gave limited results for now, such as a CG calculator for example.

If you have some improvement ideas, please see the [contribution section](#Contribution).

Also, I could eventually host the program online if there is a demand for it.

## Getting started

### Installation

For now, 2 ways are available to use this tool :

1. **From the source code** (all platforms): this project was coded using Python 3. All you have to do is to download the source code, make sure you have Python 3 and all packages in *requirements.txt* installed and to start *RC_Calc.py*.
1. **Using the binaries** (Windows only): download the latest stable version of *RC-Calc.exe* and start it.

:arrow_forward: Download the latest stable version of those files on the [release page](https://github.com/Gregczc/RC-Calc/releases).:arrow_backward:

Be aware that RC-Calc will build a database in the *db* folder, so be careful to save its content when moving to a different version of the software.

### Documentation
A detailed documentation is on its way using Sphinx.

## Contribution

Massive thanks to [@Raymas](https://github.com/raymas) for his help through this project !

If you have some ideas of features you would like to see in this program, feel free to open an issue. If you are unfamiliar with Github, contacting me on [facebook](https://www.facebook.com/gregoire.cahuzac/) or by email (gregoire.cahuzac@outlook.fr) is also fine.

Please keep in mind I am not a professional developer. Just doing this for fun in my spare time and using it as a learning platform to get better at coding and at using GitHub.
