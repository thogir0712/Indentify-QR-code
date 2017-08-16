# Change Log

## 0.3.3 (2017-08-16)
* Added `app_name` namespace to `qr_code.urls` (better compatibility with `include()` function provided with Django >= 1.9).
* Update documentation regarding the inclusion of `qr_code.urls` for distinct versions of Django.
* Minor improvements to the documentation.

## 0.3.2 (2017-08-13)
* Allows optional installation of Pillow (PNG format unavailable, fallback to SVG).
* Fixed caching of images (not working due protection against external queries).
* Fixed conditional view processing (HTTP 304) for rendered QR codes (not working due protection against external queries).

## 0.3.1 (2017-08-12)
* Added a mention about Pillow library requirement in documentation.
* Minor improvements to the documentation and the demo application.

## 0.3.0 (2017-08-12)
* Added new tag qr_url_from_text:
    * Separate image from the page displaying the image
    * Handle caching of images
    * Conditional view processing (HTTP 304) for rendered QR codes
    * Protection against external requests
    * Settings to configure URLs accesses as a service for generating QR code images
    * Added documentation for new features
    * Added tests for new features
    * Added examples to demo site
* More robust testing of make_qr_code's arguments.
* Improved documentation.
* Demo site is compatible with Django 1.8.
* Added support for Docker Compose for running the demo application and running the tests.

## 0.2.1 (2017-08-05)
* Added support for Django 1.8.
* Fixed version specifiers for Django requirement so that it wont force the installation of Django 1.11.
* Added badges for PyPi, Read the Docs and Travis CI to readme file.
* Several additions to the documentation.

## 0.2.0 (2017-08-04)
* Added support for PNG image format via an `img` tag.
* Added documentation for users and developers.
* Improved examples in demo app.

## 0.1.1 (2017-08-02)
First public release.