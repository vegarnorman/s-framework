# S

The design-oriented Sass microframework for quick and easy web development. Grids, typography, vertical rhythm and other design tools packaged are nicely into one tiny framework so you can spend more time actually designing and building your website. Comes well-documented and ready to roll. A word of warning, though; S does not come with cross-browser CSS rules. Please use it in conjunction with Autoprefixer or PostCSS for optimal multi-device performance.


## What it contains

+ A modular file structure that is easy to understand
+ Well-documented and explained Sass code so you can get started quickly
+ A grid system that is easy to use, either through classes, [attribute modules](http://amcss.github.io), or simply through mixins (no generated CSS rules!)
+ A system for typographic scaling and vertical rhythm


## How to use

Using your Sass compiler of choice, simply compile `master.css`. Done. Your design should typically go into `/modules/page-components`, either into `_page-components.scss` or preferably into smaller files for modularization purposes.
