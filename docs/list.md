# Color combinations
Hey whatsapp guys, in this file i'll add all my custom version of n1-mdl, if you want to add your custom fork this repo and make a pull request!

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

<h3 align="center"> :heart: </h3>