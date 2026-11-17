# Backdrop Template Hierarchy
A smarter and flexible template hierarchy

## Requirements
* [ClassicPress](https://www.classicpress.net)
* [WordPress](https://wordpress.org)
* [PHP 7.4](https://www.php.net/releases/7_4_0.php)
* [Composer](https://getcomposer.org)

## Registering and Booting
Add the provider before booting the Backdrop application.
<pre>
$theme->provider( Backdrop\Template\Hierarchy\Provider::class );
</pre>

Then get the template hierarchy for the current page view, without the `.php` extension, with
<pre>
Backdrop\Template\Hierarchy\hierarchy();
</pre>

Templates are looked up inside the theme's views folder (`resources/views` by default, see `backdrop-dev/template-helpers`).

## Copyright and Licenses
This project is licensed under the GNU GPL, version 2 or later.

2019–2023 © Benjamin Lu