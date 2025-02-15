<h1>Version 3X and able contains breaking changes</h1>
On android version 3x or greater contains breaking changes to the encrypt and decrypt functions.
Please use the pre-3-changes if you need the older logic

<h1>Bencoding.Securely</h1>

Securely provides building blocks to create secure Titanium apps.

The following proxy objects allow for you to build a composible cross-platform security layer to meet your various security requirements.

<h2>Important grade information</h2>

If you are using securely in your application now, there are breaking changes in version 2.x.  These changes will be put in place to improve your default security. 

Examples of the new Secure Properties storageType and securityLevel functionality are available [here](https://gist.github.com/benbahrenburg/5a8a25e7aa518ba55bd4).

The documentation will be updated when there is an opportunity. If you'd like to contribute please send a PR with the update.

<h2>Before you start</h2>
* These are iOS and Android native modules designed to work with Titanium SDK 5.1.0.GA and later.
* Before using this module you first need to install the package. If you need instructions on how to install a 3rd party module please read this installation guide.

<h2>Download the compiled release</h2>

Download the platform you wish to use:

* [iOS Dist](https://github.com/mbender74/Securely/tree/master/iOS/dist)
* [Android Dist](https://github.com/mbender74/Securely/tree/master/Android/dist)

<h2>Building from source?</h2>

If you are building from source you will need to do the following:

Import the project into Xcode:

* Modify the titanium.xcconfig file with the path to your Titanium installation

Import the project into Eclipse:

* Update the .classpath
* Update the build properties

<h2>Setup</h2>

* Download the latest release from the releases folder ( or you can build it yourself )
* Install the bencoding.securely module. If you need help here is a "How To" [guide](https://wiki.appcelerator.org/display/guides/Configuring+Apps+to+Use+Modules). 
* You can now use the module via the commonJS require method, example shown below.

<pre><code>
var securely = require('bencoding.securely');
</code></pre>

<h2>Creating the Securely Module Object</h2>

Requiring the module into your project

<pre><code>
//Require the securely module into your project
var securely = require('bencoding.securely');
</code></pre>

<h2>Secure Properties</h2>

The Securely Properties module is used to store values in the KeyChain using the same API as Titanium.App.Properties. 

To learn more about this part of the module, please view the documentation [here](https://github.com/benbahrenburg/Securely/blob/master/Documentation/properties.md).

----

<h2>Key Generators</h2>

Securely provides the ability to generator random and derived keys.  These key generators allow you to generate strong passwords for your encryption functions.

To learn more about this part of the module, please view the documentation [here](https://github.com/benbahrenburg/Securely/blob/master/Documentation/keymakers.md).


----

<h2>String Crypto</h2>

Securely provides the ability to encrypt and decrypt JavaScript strings and JSON objects through a variety of algorithms.

To learn more about this part of the module, please view the documentation [here](https://github.com/benbahrenburg/Securely/blob/master/Documentation/strings.md).


----


<h2>File Crypto</h2>

Securely provides the ability to encrypt and decrypt local device files.

To learn more about this part of the module, please view the documentation [here](https://github.com/benbahrenburg/Securely/blob/master/Documentation/files.md).


----

<h2>iOS PDF Locker</h2>

On iOS Securely provides the ability to password protect and unlock PDF documents.

To learn more about this part of the module, please view the documentation [here](https://github.com/benbahrenburg/Securely/blob/master/Documentation/pdfs.md).


----

<h2>Dependent Projects</h2>
Securely uses several wonderful open source projects.  I highly encourage you to check them out using the information below.

JSONKit 

Project: [http://github.com/johnezang/JSONKit](http://github.com/johnezang/JSONKit)

sskeychain

Project: [https://github.com/soffes/sskeychain)


<h2>Licensing & Support</h2>

This project is licensed under the OSI approved Apache Public License (version 2). For details please see the license associated with each project.

Developed by [Ben Bahrenburg](http://bahrenburgs.com) available on twitter [@bencoding](http://twitter.com/bencoding)

<h2>Learn More</h2>

<h3>Examples</h3>
Please check the module's example folder or [github repo](https://github.com/benbahrenburg/Securely/tree/master/iOS/example) for samples on how to use this project.

<h3>Twitter</h3>

Please consider following the [@bencoding Twitter](http://www.twitter.com/bencoding) for updates 
and more about Titanium.

<h3>Blog</h3>

For module updates, Titanium tutorials and more please check out my blog at [bencoding.Com](http://bencoding.com).
