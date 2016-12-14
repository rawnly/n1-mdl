# Black
This is a black and white color combination.

### Screenshots
![main](../img//black/main.png)
![email](../img//black/email.png)
![accounts](../img//black/accounts.png)
![appareance](../img//black/appareance.png)

### Code

```less
/* user.less */

// For Navbar and Settings.
// Default @green
@primary : @black;

// For url hovers and open thread.
// Default @green-A
@secondary : @white;

// All background except for sidebar.
// Default @white
@background : @white;

// Sidebar background
// Default darken(@background, 2%)
@sidebar-background : darken(@background, 2%);

// Text Color
// Default constrast(@background)
@user-text-color : contrast(@background);
```
