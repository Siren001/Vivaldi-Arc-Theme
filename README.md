# Vivaldi Arc Theme

Arc for Vivaldi is a set of custom CSS files that integrate Vivaldi's UI with [Arc](https://github.com/jnsh/arc-theme), a popular GTK theme. Rework of **Tiamarth's** [original theme](https://github.com/Tiamarth/Arc-for-Vivaldi) for Vivaldi.

## Screenshots

#### Arc
<div align="left"><img src="screenshots/light.png" alt="Preview" /></div>

#### Arc-Dark
<div align="left"><img src="screenshots/dark.png" alt="Preview" /></div>

#### Arc-Darker
<div align="left"><img src="screenshots/darker.png" alt="Preview" /></div>
<br>
<div align="left"><img src="screenshots/darker2.png" alt="Preview" /></div>

## Features

- Remove Vivaldi's header gradient
- When tabs are not at the top of the window, merge address bar with header
- Use Arc's window buttons even when Native Window is disabled in the settings (optional)
- Use Arc's sidebar color even on light themes

## Installation

#### 1. Install custom CSS files

- In Vivaldi, open `vivaldi://experiments`
- Select the `Allow for using CSS modifications` checkbox
- Open the `Appearance` page in Vivaldi settings
- In the `CUSTOM UI MODIFICATIONS` section, select the folder where you have saved the Vivaldi Arc theme files (`arc.css`, `arc-window.css` and `arc` folder)

#### 2. Configure Vivaldi theme settings

This custom CSS integrates settings in Vivaldi's built-in theme editor (the custom CSS is necessary to integrate with Arc because you cannot currently customize every aspect of Vivaldi from the editor).

Go to the themes setting page, and add the Arc themes with the following settings:

| Arc                               | Arc-Dark                          | Arc-Darker                        |
| --------------------------------- | --------------------------------- | --------------------------------- |
| Background: #f6f7f8               | Background: #383c4a               | Background: #f6f7f8               |
| Foreground: #3b3e45               | Foreground: #d3dae3               | Foreground: #3b3e45               |
| Highlight: #5294e2                | Highlight: #5294e2                | Highlight: #5294e2                |
| Accent: #e7e8eb                   | Accent: #2f343f                   | Accent: #2f343f                   |
| [ ] Accent Color from Active Page | [ ] Accent Color from Active Page | [ ] Accent Color from Active Page |
| [x] Apply Accent Color to Window  | [x] Apply Accent Color to Window  | [x] Apply Accent Color to Window  |
| [x] Transparent Tabs              | [x] Transparent Tabs              | [x] Transparent Tabs              |
| Corner Rounding: 3px              | Corner Rounding: 3px              | Corner Rounding: 3px              |

Configure the start page background color (`Settings -> Start Page`) as follows:

| Arc                               | Arc-Dark                          | Arc-Darker                        |
| --------------------------------- | --------------------------------- | --------------------------------- |
| Background: #f6f7f8               | Background: #383c4a               | Background: #f6f7f8               |

**Note**: *Arc's scrollbars only get applied to internal pages and, as far as I know, there's nothing that can be done about that from within a custom css file for Vivaldi. A userstyle by Tiamarth to apply Arc scrollbars on websites can be found [here](https://userstyles.org/styles/142645/arc-scrollbars)*.  

### Arc Window Buttons

If you do not want to **use the Arc window buttons**, delete the `arc-window.css` file and the `arc` sub-folder from the folder where you have saved the Vivaldi Arc theme files.

### Custom Arc Color

If you are using a custom version of the Arc theme(s) that uses a color that is different from the standard Arc blue, just change the `Highlight` color in the table above from `#5294e2` to your preferred color.  
For example:

- Manjaro green: `#34be5b`
- Ubuntu orange: `#dd4814`

## Todo

- [ ] Tab strip (tabs left/right)
- [ ] Arc-Lighter theme

----

[Original AFV thread on the Vivaldi forums](https://forum.vivaldi.net/post/137297)  
