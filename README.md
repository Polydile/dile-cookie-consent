# \<dile-cookie-consent\>

Polymer Web Component to implement a cookie consent.

This components accepts a "role" property to styling.

When you click on the button create a cookie in navigator.
If cookie is created, the component is not visible, in other case is visible.

```html
<dile-cookie-consent
  text =' ... '
  label-button='Ok'
  role="primary"
  position="bottom"
  name-cookie="dile"
  days-expiration-cookie=365
></dile-cookie-consent>
```

Property | Description | Default
---------|-------------|---------
text | Text of consent. | {}
label-button | Label of button | Ok
role | undefined, primary, danger, success, warning | danger
position | 'top' => Top of screen, 'bottom' => Bottom of screen | bottom
name-cookie | Cookie's name | dile
days-expiration-cookie | Number of days expiration of cookie

Custom property | Description | Default
----------------|-------------|---------
--dile-cookie-consent-background-color | Background color | gray