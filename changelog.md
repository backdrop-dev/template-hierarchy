# Changelog

## 1.0.0 - November 17, 2026
The first official release of Backdrop Template Hierarchy for Backdrop 2.0. It extends the core WordPress template hierarchy, captures the full hierarchy for the current page (`Backdrop\Template\Hierarchy\hierarchy()`) and looks for templates in the theme's views folder.

Changed:
* Requires `backdrop-dev/framework` ^2.0 and `backdrop-dev/template-helpers` ^1.0.1, which the package uses but didn't declare.
* Removed an unused variable in `Component::single()`.
