<div align="center">
	<a href="https://www.qloapps.com"><img src="https://forums.qloapps.com/assets/uploads/system/site-logo.png?v=hkl8e1230fo" alt="QloApps"></a>
	<br>
	<p>
		<b>QloApps - An open source and free platform to launch your own hotel booking website</b>
	</p>
</div>

<p align="center">
	<a href="https://packagist.org/packages/bagisto/bagisto"><img src="https://poser.pugx.org/bagisto/bagisto/d/total.svg" alt="Download"></a>
	<a href="https://packagist.org/packages/bagisto/bagisto"><img src="https://poser.pugx.org/sumitwebkul/test-composer/v" alt="Latest Stable Version"></a>
	[![Latest Stable Version](https://poser.pugx.org/sumitwebkul/test-composer/v)](//packagist.org/packages/sumitwebkul/test-composer)
	<a href="https://packagist.org/packages/bagisto/bagisto"><img src="https://poser.pugx.org/bagisto/bagisto/license.svg" alt="License"></a>
	<a href="https://github.com/bagisto/bagisto/actions"><img src="https://github.com/bagisto/bagisto/workflows/CI/badge.svg" alt="Forum"></a>
	<a href="https://github.com/bagisto/bagisto/actions"><img src="https://github.com/bagisto/bagisto/workflows/CI/badge.svg" alt="Support"></a>
	<a href="https://github.com/bagisto/bagisto/actions"><img src="https://github.com/bagisto/bagisto/workflows/CI/badge.svg" alt="Contribute"></a>

</p>

## Topics
1. [Introduction](#introduction)
3. [Requirements](#requirements)
4. [Installation & Configuration](#installation-and-configuration)
5. [License](#license)
6. [Security Vulnerabilities](#security-vulnerabilities)
2. [Documentation & Demo](#documentation)
7. [Contribute](#miscellaneous)

### Introduction

QloApps also known as Qlo is an **Open-source and Free hotel reservation system** and booking engine. <br>
With the help of QloApps, you can launch your hotel booking website without any cost and take & manage online bookings . You can manage your online & On-Desk booking easily with QloApps.<br>
QloApps is forked from Prestashop. In order to develope QloApps PS 1.6.1.1 was used.

### Requirements

* **OS**: Ubuntu 16.04 LTS or higher / Windows 7 or Higher (WampServer / XAMPP).
* **SERVER**: Apache 2 or NGINX.
* **RAM**: 3 GB or higher.
* **PHP**: 7.3 or higher.
* **Processor**: Clock Cycle 1 Ghz or higher.
* **For MySQL users**: 5.7.23 or higher.
* **For MariaDB users**: 10.2.7 or Higher.
* **Node**: 8.11.3 LTS or higher.
* **Composer**: 1.6.5 or higher.

### Installation and Configuration

**1. You can install Bagisto by using the GUI installer.**

##### a. Download zip from the link below:

[Download the latest release](https://github.com/bagisto/bagisto/releases/latest)

##### b. Extract the contents of zip and execute the project in your browser:

~~~
http(s)://localhost/bagisto/public
~~~

or

~~~
http(s)://example.com/public
~~~

**2. Or you can install Bagisto from your console.**

##### Execute these commands below, in order

~~~
1. composer create-project bagisto/bagisto-standard
~~~

~~~
2. php artisan bagisto:install
~~~

**To execute Bagisto**:

##### On server:

Warning: Before going into production mode we recommend you uninstall developer dependencies.
In order to do that, run the command below:

> composer install --no-dev

~~~
Open the specified entry point in your hosts file in your browser or make an entry in hosts file if not done.
~~~

##### On local:

~~~
php artisan serve
~~~


**How to log in as admin:**

> *http(s)://example.com/admin/login*

~~~
email:admin@example.com
password:admin123
~~~

**How to log in as customer:**

*You can directly register as customer and then login.*

> *http(s)://example.com/customer/register*


### License
Bagisto is a truly opensource E-Commerce framework which will always be free under the [MIT License](https://github.com/bagisto/bagisto/blob/master/LICENSE).

### Security Vulnerabilities
Please don't disclose security vulnerabilities publicly. If you find any security vulnerability in Bagisto then please email us: mailto:support@bagisto.com.

### Documentation & Demo

#### QloApps Documentation [https://qloapps.com/qlo-reservation-system](https://qloapps.com/qlo-reservation-system)
#### QloApps Demo
**FrontEnd** : http://demo.qloapps.com </br>
**Backend** : http://demo.qloapps.com/adminhtl/index.php </br>
**username** : demo@demo.com </br>
**Password** : demodemo </br>

#### Contribute

This project is on [Open Collective](https://opencollective.com/bagisto) and it exists thanks to the people who contribute.

<a href="https://github.com/bagisto/bagisto/graphs/contributors"><img src="https://opencollective.com/bagisto/contributors.svg?width=890&button=false"/></a>

#### Backers

Thank you to all our backers! ??

<a href="https://opencollective.com/bagisto#contributors" target="_blank"><img src="https://opencollective.com/bagisto/backers.svg?width=890"></a>

#### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website.

<a href="https://opencollective.com/bagisto/contribute/sponsor-7372/checkout" target="_blank"><img src="https://images.opencollective.com/static/images/become_sponsor.svg"></a>
