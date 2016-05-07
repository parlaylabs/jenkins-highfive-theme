![image](https://parlaylabs.github.io/jenkins-highfive-theme/images/logo.svg)
# jenkins-highfive-theme
Beautify your Jenkins with the Highfive theme!

Website: https://parlaylabs.github.io/jenkins-highfive-theme

This is a Highfive-themed fork of [Jenkins Material Theme](http://afonsof.com/jenkins-material-theme).

## Features
* Just one small css file (35K)
* Embed minified SVG images
* Multiple ways to install
* Customize the color and logo using the [generator][generator]

## Screenshots

**TODO: Update these screenshots**

[![Screenshot jenkins-material-theme main](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-main.png)](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-main-large.png)      [![Screenshot jenkins-material-theme legend](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-legend.png)](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-legend-large.png) [![Screenshot jenkins-material-theme console](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-console.png)](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-console-large.png)
[![Screenshot jenkins-material-theme history](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-history.png)](http://afonsof.com/jenkins-material-theme/images/screenshot-jenkins-theme-material-history-large.png)


## Installation 

### Using this GitHub page (recommended) (auto-updated)

1. Install [Jenkins Simple Theme Plugin][simple]

2. Click `Manage Jenkins`

3. Click `Configure System` and scroll down to `Theme`

4. Set the CSS field to `https://parlaylabs.github.io/jenkins-highfive-theme/dist/material-light.css`.

5. Click `Save`

## Development

CSS file are minified and compressed with Grunt. To prepare the environment:

```
npm install
grunt
```

This will generate the following file:
- dist/material-light.css

## Compatibility
- Simple Theme plugin 0.3
- Jenkins 1.636
- Firefox 3.5+
- Chrome 4+
- Safari 4+
- Opera 15+
- Microsoft IE11 and Edge


If you are experiencing issues please let me know! Also, feel free to contribute!

## License
http://afonsof.mit-license.org/

## Thanks to
- [Simple Theme Plugin][simple] for the Simple Theme plugin
- [Google][google] for the the material design inspiration and the icons
- [Material Design Icons][material-design-icons] for some extra icons
- [Stylish][stylish] for making the test of new versions easy
- [canon-jenkins][canon-jenkins] for the base theme
- [@Heldroe][heldroe] for Firefox and Microsoft support
- [@bootstraponline][bootstraponline] for Jenkins native plugin

[simple]: https://wiki.jenkins-ci.org/display/JENKINS/Simple+Theme+Plugin
[google]: https://www.google.com/design/spec/material-design/introduction.html
[material-design-icons]: https://materialdesignicons.com/
[stylish]: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe
[canon-jenkins]: https://github.com/rackerlabs/canon-jenkins
[heldroe]: https://github.com/Heldroe
[generator]: http://afonsof.com/jenkins-material-theme
[bootstraponline]: https://github.com/bootstraponline
