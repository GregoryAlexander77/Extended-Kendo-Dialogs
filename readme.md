# Kendo UI Extended Message Box API

The Kendo UI Extended Message Box extends the Kendo UI Framework with additional message box widgets. The ExtWaitDialog has been themed to work with all Kendo UI less based themes.


## Kendo UI Web Extended Widgets

+ ExtDialog - Extends the Kendo.ui.Window
+ ExtAlertDialog - Alert Dialog
+ ExtInputDialog - Input Dialog
+ ExtOkCancelDialog - Ok/Cancel Dialog
+ ExtYesNoDialog - Yes/No Dialog
+ ExtWaitDialog - Wait Dialog.

## Articles on How to Use the Kendo UI Web Extended Widgets

+ [Kendo UI Extended API: DropDownTreeView Widget](http://www.aspnetwiki.com/page:kendoui-ext-api-dropdowntreeview)
+ [Kendo UI Extended API: DropDownGrid Widget](http://www.aspnetwiki.com/page:kendoui-ext-api-dropdowngrid)
+ [Kendo UI Extended API: MessageBox Dialogs](http://www.aspnetwiki.com/page:kendoui-ext-api-messagebox-dialogs)
+ [Kendo UI Extended API: BorderLayout Widget](http://www.aspnetwiki.com/page:kendoui-ext-api-borderlayout)


## Adding Kendo UI Web Extended API to Your Application

### Adding the StyleSheet

Add the contents of the styles folder to your application.  In the HTML file, add a reference to kendo.ext.css.  For example:

```html
<link href="//cdn.kendostatic.com/2012.3.1315/styles/kendo.common.min.css" rel="stylesheet" />
<link href="//cdn.kendostatic.com/2012.3.1315/styles/kendo.default.min.css" rel="stylesheet" />
<link href="./styles/kendoext/kendo.ext.css" rel="stylesheet" />
````

### Adding the JavaScript

Add the contents of the js folder to your application.  In the HTML file, define the reference to the kendo.web.ext.js after the references to the jQuery and Kendo UI JavaScript files.  For example:

```html
<script src="//code.jquery.com/jquery-1.8.2.min.js"></script>
<script src="//cdn.kendostatic.com/2012.3.1315/js/kendo.all.min.js"></script>
<script src="./scripts/kendo.web.ext.js"></script>
````


## Authors

John DeVight
Gregory Alexander


## License
> Copyright (C) 2013 John DeVight
Gregory Alexander modified the library and created animations that match the Kendo UI themes.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software,
and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions
of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED
TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.