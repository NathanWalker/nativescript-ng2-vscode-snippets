## NativeScript + Angular Snippets for Visual Studio Code

Now compatible with Angular 4.x and above.

This JSON file contains snippets for all NativeScript UI components and some frequently used attributes specifically for use with [nativescript-angular](https://github.com/NativeScript/nativescript-angular).

All UI components are prefixed with `ns`. Attributes do not have a prefix.

![Preview](https://cdn.filestackcontent.com/IcTER9raRgCi8nCQeOZu?v=0)

### UI Components

#### From within TypeScript `Component` Files:

- Component with inline template - `nscomponent_template`
- Component with templateUrl - `nscomponent_templateUrl`
- Modal Component with inline template - `nsmodal_template`
- Modal Component with templateUrl - `nsmodal_templateUrl`

The following can be used inside both TypeScript and HTML view files:

#### Layouts

- Absolute Layout - `nsabsolute`
- Dock Layout - `nsdock`
- Flexbox Layout - `nsflexbox`
- Grid Layout - `nsgrid`
- Stack Layout - `nsstack`
- Wrap Layout - `nswrap`

### Widgets

- Action Bar - `nsactionbar`
- Action Bar with Back Button - `nsactionbarback`
- Label - `nslabel`
- Label with Formatted String - `nslabel_formatted`
- Text Field - `nstextfield`
- Secure Text Field (for passwords) - `nspassword`
- Text View - `nstextview`
- Image - `nsimg`
- Border - `nsborder`
- Button - `nsbtn`
- Button with Formatted String - `nsbtn_formatted`
- Search Bar - `nssearchbar`
- Switch - `nsswitch`
- Slider - `nsslider`
- Progress - `nsprogress`
- Activity Indicator - `nsloading`
- Date Picker - `nsdate`
- Time Picker - `nstime`
- List Picker - `nslistpicker`
- Segmented Bar - `nssegmentedbar`
- Tab View - `nstabview`
- List View - `nslistview`
- Web View - `nswebview`

### Attributes

- cssClass - `css`
- text - `text`
- icon - `icon`
- tap - `tap`
- textWrap - `wrap`
- horizontalAlignment - `halign`
- verticalAlignment - `valign`
- visibility - `visibility`
- stretch - `stretch`
- keyboardType - `kbtype`
- colSpan - `colspan`
- rowSpan - `rowspan`
- row - `row`
- col - `col`
- width - `width`
- height - `height`

### Helpers

- showModal - `nsmodal_showModal`

## How to use?

1. Inside Visual Studio Code press
```bash
CTRL + P
```
2. Type the following in the console window
```bash
ext install nativescript-ng2-snippets
```

3. Hit enter.
