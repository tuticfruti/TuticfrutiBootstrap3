#Table of contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [TuticfrutiBootstrap3 Sublime Text Plugin](#tuticfrutibootstrap3-sublime-text-plugin)
- [Features](#features)
- [Pre-requisites](#pre-requisites)
- [Getting Started](#getting-started)
- [Snippets](#snippets)
  - [CSS](#css)
    - [Grid system](#grid-system)
      - [Snippets](#snippets-1)
      - [Classes](#classes)
      - [Demo](#demo)
    - [Typography](#typography)
      - [Snippets](#snippets-2)
      - [Classes](#classes-1)
      - [Demo](#demo-1)
    - [Code](#code)
      - [Snippets](#snippets-3)
      - [Classes](#classes-2)
    - [Tables](#tables)
      - [Snippets](#snippets-4)
      - [Classes](#classes-3)
      - [Demo](#demo-2)
    - [Forms](#forms)
      - [Snippets](#snippets-5)
      - [Classes](#classes-4)
      - [Demo](#demo-3)
    - [Buttons](#buttons)
      - [Snippets](#snippets-6)
      - [Classes](#classes-5)
      - [Demo](#demo-4)
    - [Images](#images)
      - [Snippets](#snippets-7)
      - [Classes](#classes-6)
      - [Demo](#demo-5)
    - [Helper classes](#helper-classes)
      - [Snippets](#snippets-8)
      - [Classes](#classes-7)
      - [Demo](#demo-6)
    - [Responsive utilities](#responsive-utilities)
      - [Classes](#classes-8)
  - [Components](#components)
    - [Glyphicons](#glyphicons)
      - [Snippets](#snippets-9)
      - [Classes](#classes-9)
      - [Demo](#demo-7)
    - [Dropdowns](#dropdowns)
      - [Snippets](#snippets-10)
      - [Classes](#classes-10)
      - [Demo](#demo-8)
    - [Button groups](#button-groups)
      - [Snippets](#snippets-11)
      - [Classes](#classes-11)
      - [Demo](#demo-9)
    - [Input groups](#input-groups)
      - [Snippets](#snippets-12)
      - [Classes](#classes-12)
      - [Demo](#demo-10)
    - [Navs](#navs)
    - [Navbar](#navbar)
    - [Breadcrumbs](#breadcrumbs)
    - [Pagination](#pagination)
    - [Labels](#labels)
    - [Badges](#badges)
    - [Jumbotron](#jumbotron)
    - [Page header](#page-header)
    - [Tumbnails](#tumbnails)
    - [Alerts](#alerts)
    - [Progress bars](#progress-bars)
    - [Media object](#media-object)
    - [List group](#list-group)
    - [Panels](#panels)
    - [Responsive embed](#responsive-embed)
    - [Wells](#wells)
  - [Javascript](#javascript)
  - [Templates](#templates)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# TuticfrutiBootstrap3 Sublime Text Plugin
A complete and reusable set of Bootstrap3 snippets for Sublime Text editor.

# Features
- [Bootstrap3](http://getbootstrap.com/).
- [Predefined classes auto-completion](https://github.com/tuticfruti/TuticfrutiBootstrap3/blob/master/snippets/all-classes.sublime-completions "all-classes.sublime-completions").
- [CSS](http://getbootstrap.com/css/), [Components](http://getbootstrap.com/components/) and [Javascript](http://getbootstrap.com/javascript/) (comming soon) snippets.
- Reusable components.
- [Youtube video demo](https://www.youtube.com/playlist?list=PLL0QEvkK-t2BxBobyy2C1P_JHg6zdeaMs "TuticfrutiBootstrap3 playlist").

# Pre-requisites
    Sublime text 2/3?
    Bootstrap 3 (version ?).
    Package manager if you install from package manager.
    Jquery (version ?).


# Getting Started
Installation.
    Manual installation. ZIP.
    Add repository. Local package manager.
    From packages.io. Install package manager.


How to use.
    Two types of snippets: classes snippets (into tag element double quotes) and component snippets (into html document, not into tag element).

    Alt + / (Edit > Show Completions menu option)

All component snippets begins with 'b' (Bootstrap) key. Class snippets are Bootstrap class literals.

Examples:

# Snippets

## CSS
### Grid system
Bootstrap includes a responsive, mobile first fluid grid system that appropriately scales up to 12 columns as the device or viewport size increases.

####Snippets
| Snippet           | Tab trigger          |
| ----------------- | -------------------- |
| Container         | `bcontainer`         |
| Fluid container   | `bcontainer-fluid`   |
| Grid row          | `bgrid-row`          |
| Grid column       | `bgrid-col`          |

####Classes
- `container`
- `container-fluid`
- `row`
- `col`
- `col-(xs|sm|md|lg)-(1-12)`
- `col-(xs|sm|md|lg)-push-(1-12)`
- `col-(xs|sm|md|lg)-pull-(1-12)`
- `col-(xs|sm|md|lg)-offset-(1-12)`

####Demo
[Grid system demo](https://).

### Typography

####Snippets
| Snippet                      | Tab trigger                     |
| ---------------------------- | ------------------------------- |
| Headings                     | `btypografy-header`             |
| Lead body copy               | `btypografy-lead`               |
| Marked text                  | `btypografy-mark`               |
| Small text                   | `btypografy-small`              |
| Alignment classes            | `btypografy-text-align`         |
| Transformation classes       | `btypografy-text-trans`         |
| Initialism                   | `btypografy-initialism`         |
| Blockquote with footer       | `btypografy-blockquote-footer`  |
| Reverse blockquote           | `btypografy-blockquote-reverse` |
| Lists (unstyled|inline)      | `btypografy-list`               |
| Horizontal description list  | `btypografy-list-hdescription`  |

####Classes
- `h(1-6)`
- `lead`
- `mark`
- `small`
- `text-(left|center|right|justify|nowrap)`
- `text-(lowercase|uppercase|capitalize)`
- `initialism`
- `blockquote-reverse`
- `list-(style|unstyled|inline)`
- `dl-horizontal`

####Demo
[Typografy demo](https://).

### Code

####Snippets
| Snippet           | Tab trigger          |
| ----------------- | -------------------- |
| Block scrollable  | `bcode-block-scroll` |

####Classes
- `pre-scrollable`

### Tables

####Snippets
| Snippet           | Tab trigger          |
| ----------------- | -------------------- |
| Default table     | `btable-default`     |
| Responsive table  | `btable-responsive`  |
| Table row         | `btable-tr`          |
| Table td          | `btable-td`          |
| Table th          | `btable-th`          |

####Classes
- `table`
- `table-responsive`
- `table-stripped`
- `table-bordered`
- `table-hover`
- `table-condensed`
- `active|success|info|warning|danger`

####Demo
[Tables demo](https://).

### Forms

####Snippets
| Snippet                 | Tab trigger                |
| ----------------------- | -------------------------- |
| Default form            | `bform-default`            |
| Default form group      | `bform-group-default`      |
| Input control           | `bcontrol-input`           |
| Inline input control    | `bcontrol-input-inline`    | 
| Textarea control        | `bcontrol-textarea`        |
| Radio control           | `bcontrol-radio`           |
| Inline Radio control    | `bcontrol-radio-inline`    |
| Checkbox control        | `bcontrol-checkbox`        |
| Inline checkbox control | `bcontrol-checkbox-inline` |
| Select control          | `bcontrol-select`          |
| Inline select control   | `bcontrol-select-inline`   |
| Static control          | `bcontrol-static`          |
| Inline static control   | `bcontrol-static-inline`   |
| Submit button           | `bcontrol-submit`          |
| Inline submit button    | `bcontrol-submit-inline`   |
| Help text               | `bcontrol-help`            |
| Label                   | `bcontrol-label`           |
| Inline Label            | `bcontrol-label-inline`    |
| Field set               | `bform-fieldset`           |

####Classes
- `form-inline`
- `form-horizontal`
- `form-group`
- `form-group-(sm|lg)`
- `form-control`
- `text|password|datetime|date|month|time|week|number|email|url|search|tel|color|datetime-local`
- `radio`
- `radio-inline`
- `checkbox`
- `checkbox-inline`
- `control-label`
- `form-control-static`
- `active`
- `desabled`
- `readonly`
- `has-(success|warning|error)`
- `input(sm|lg)`
- `help-block`

####Demo
[Forms demo](https://).

### Buttons

####Snippets
| Snippet           | Tab trigger          |
| ----------------- | -------------------- |
| Default button    | `bbutton-default`    |
| Link button       | `bbutton-link`       |

####Classes
- `btn`
- `btn-(default|primary|success|info|warning|danger|link)`
- `btn-(xs|sm|lg)`
- `btn-block`
- `active`
- `disabled`

####Demo
[Buttons demo](https://).

### Images

####Snippets
| Snippet           | Tab trigger          |
| ----------------- | -------------------- |
| Default image     | `bimage-default`     |

####Classes
- `img-responsive`
- `img-rounded`
- `img-circle`
- `img-thumbnail`

####Demo
[Images demo](https://).

### Helper classes

####Snippets
| Snippet                | Tab trigger            |
| ---------------------- | ---------------------- |
| Contextual colors      | `bhelper-color`        |
| Contextual backgrounds | `bhelper-background`   |
| Close icon             | `bhelper-close-icon`   |
| Carets                 | `bhelper-caret`        |
| Quick floats           | `bhelper-float`        |
| Center content blocks  | `bhelper-center-block` |
| Clearfix               | `bhelper-clearfix`     |
| Showing and hiding     | `bhelper-visibility`   |
| Screen reader          | `bhelper-sr-default`   |
| Screen reader          | `bhelper-sr-link`      |

####Classes
- `text-(muted|primary|success|info|warning|danger)`
- `bg-(primary|success|info|warning|danger)`
- `caret`
- `pull-(left|right)`
- `center-block`
- `clearfix`
- `show|hidden`
- `sr-only`
- `sr-only-focusable`
- `text-hide`

####Demo
[Helpers demo](https://).

### Responsive utilities
For faster mobile-friendly development, use these utility classes for showing and hiding content by device via media query. Also included are utility classes for toggling content when printed.

####Classes
- `visible-(xs|sm|md|lg)`
- `visible-(xs|sm|md|lg)-block`
- `visible-(xs|sm|md|lg)-inline`
- `visible-(xs|sm|md|lg)-inline-block`
- `hidden-(xs|sm|md|lg)`
- `visible-print-(block|inline|inline-block)`
- `hidden-print`

## Components
### Glyphicons
Includes over 250 glyphs in font format from the Glyphicon Halflings set ([Glyphicons homepage](http://glyphicons.com/)).

####Snippets
| Snippet           | Tab trigger          |
| ----------------- | -------------------- |
| Default glyphicon | `bglyphicon-default` |
| Glyphicon button  | `bbutton-glyphicon`  |

####Classes
- `glyphicon`
- `glyphicon-(home|user|star|exclamation-sign|...)`

####Demo
[Glyphicons demo](https://youtu.be/u9JYaSSVgUM?list=PLL0QEvkK-t2BxBobyy2C1P_JHg6zdeaMs).

### Dropdowns
Toggleable, contextual menu for displaying lists of links. Made interactive with the dropdown JavaScript plugin.

#### Snippets
| Snippet                | Tab trigger               |
| ---------------------- | ------------------------- |
| Default dropdown       | `bdropdown-default`       |
| Default dropdown item  | `bbutton-glyphicon`       |
| Header dropdown item   | `bdropdown-item-header`   |
| Divider dropdown item  | `bdropdown-item-divider`  |
| Active dropdown item   | `bdropdown-item-active`   |
| Disabled dropdown item | `bdropdown-item-disabled` |

####Classes
- `dropdown`
- `dropup`
- `dropdown-menu`
- `dropdown-menu-left`
- `dropdown-menu-right`
- `dropdown-header`
- `active`
- `disabled`
- `divider`
- `separator`

####Demo
[Dropdowns demo](https://youtu.be/BgqjRGxhD-4?list=PLL0QEvkK-t2BxBobyy2C1P_JHg6zdeaMs).

### Button groups
Group a series of buttons together on a single line with the button group. For more complex components, combine sets of button groups into a button toolbar.

#### Snippets
| Snippet                | Tab trigger               |
| ---------------------- | ------------------------- |
| Default button group   | `bbutton-group-default`   |
| Justified button group | `bbutton-group-justified` |
| Button toolbar         | `bbutton-toolbar`         |

#### Classes
- `btn-group`
- `btn-toolbar`
- `btn-group-(xs|sm|lg)`
- `btn-group-vertical`
- `btn-group-justified`

#### Demo
[Button groups demo](https://youtu.be/BgqjRGxhD-4?list=PLL0QEvkK-t2BxBobyy2C1P_JHg6zdeaMs).

### Input groups
Extend form controls by adding text or buttons before, after, or on both sides of any text-based `<input>`. 

#### Snippets
| Snippet                        | Tab trigger                   |
| ------------------------------ | ----------------------------- |
| Default input group            | `binput-group-default`        |
| Checkboxes and radio addon     | `binput-group-radio-checkbox` |
| Button with dropdown           | `binput-group-dropdown`       |
| Button addon                   | `binput-group-button`         |
| Segmented buttons              | `binput-group-split`          |

#### Classes
- `input-group`
- `input-group-addon`
- `input-group-(sm|lg)`
- `input-group-btn`

#### Demo
[Input groups demo](https://youtu.be/-Hj7GBi3Ecs?list=PLL0QEvkK-t2BxBobyy2C1P_JHg6zdeaMs).

### Navs
### Navbar
### Breadcrumbs
### Pagination
### Labels
### Badges
### Jumbotron
### Page header
### Tumbnails
### Alerts
### Progress bars
### Media object
### List group
### Panels
### Responsive embed
### Wells

## Javascript
Comming soon.
## Templates

# License
**The MIT License (MIT)**

**Copyright (c) 2015 tuticfruti**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
