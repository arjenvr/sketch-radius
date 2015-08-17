Corner Radius Shortcuts
=======================

Sketch plugin to increase or decrease the corner radius on rectangle shapes using keyboard shortcuts.

![Sketch Radius Demo](https://github.com/arjenvr/sketch-radius/raw/master/sketch-radius-demo.gif)

##Keyboard shortcuts

| Command               | Shortcut                                         |
|-----------------------|--------------------------------------------------|
| Increase Radius       | <kbd>command</kbd> + <kbd>]</kbd>                    |
| Decrease Radius       | <kbd>command</kbd> + <kbd>[</kbd>                    |
| Increase Radius by 10 | <kbd>command</kbd> + <kbd>Shift</kbd> + <kbd>]</kbd> |
| Decrease Radius by 10 | <kbd>command</kbd> + <kbd>Shift</kbd> + <kbd>[</kbd> |

##Installation

### Download and extract ZIP
1. [Download the ZIP file containing Radius](https://github.com/arjenvr/sketch-radius/archive/master.zip)
2. Copy the contents to the plugin folder (Open up Sketch, go to `Plugins` › `Reveal Plugins Folder…` to open it.)

### Using GitHub for Mac
_NOTE: This requires [GitHub for Mac](https://mac.github.com) to be installed._

1. Click the [Clone in Desktop](github-mac://openRepo/https://github.com/arjenvr/sketch-radius) button on GitHub
2. Open up Sketch, go to `Plugins` › `Reveal Plugins Folder…` to open the plugins folder in Finder. Drag the folder by its icon from the Finder window into the Open dialog of GitHub for Mac.

## Known issues
* The radius of all corners will be set uniformly based on the radius of the top left corner. If your shape has different radii on individual corners they will be lost.
* Negative values are allowed even though these have no effect

## Acknowledgements
* Prompted by a question from [Oleg Kuroptiev](https://twitter.com/bass_blog)
* Made to mirror the keyboard shortcuts for the rounded rectangle tool in Photoshop
* Based on examples from [Sketch Plugins Cookbook](https://github.com/turbobabr/Sketch-Plugins-Cookbook)

##Contact
* [@arjenvr](https://www.twitter.com/arjenvr) on Twitter
