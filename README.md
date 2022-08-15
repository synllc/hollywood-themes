# Hollywood Themes
These are the default themes and stylesheets for Hollywood. This is a submodule imported directly into the interface, which means changes applied here will sooner or later be integrated into a future interface update.

### Files

| File | Description |
| - | - |
| `hollywood-base.scss` | The layout stylesheet. It defines all element layouts (organization, padding, margins, sizes, etc.) alongside their behavior and animations, if any. **The data in this file is global and static, applying for every theme.** |
| `_hollywood-impl.scss` | The color and variable stylesheet. It defines all **customizable** data and the default values of certain variables. **If you create a variable in this stylesheet, you must also create the assignment operation in** `_hollywood-postfix.scss`. See below for more information. |
| `_hollywood-postfix.scss` | The stylesheet inserted into the `//@STITCH` comment in a theme's main stylesheet, used a transitory file assigning theme properties/colors/options to customizable variables defined in `_hollywood-impl.scss`. |

### Contribution
Feel free to make any pull requests, but it is up to the developers' discretion to approve or reject any. If your changes are too inconsistent with our design language, it will be rejected.
