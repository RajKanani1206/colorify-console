# Colorify Console

A npm library to colorify your browser console logs build with typescript

# Installation

Run the command below to install the package inside your project

`npm i @raj1206/colorify-console`

# Import

`import {LOG} from '@raj1206/colorify-console'`

# Use

After importing the library in your file, you have three functions to colorify your logs. All these functions accepts a string

- `LOG.success();` -> To give green color
- `LOG.danger();` -> To give red color
- `LOG.info();` -> To give yellow background color with black text color

For example:-

```
LOG.success("Congratulations!"); // Print 'Congratulations!' in green color
LOG.danger("Wrong"); // Print 'Wrong' in red color
LOG.info("Info"); // Print 'Info' in black text color with yellow background color
```
