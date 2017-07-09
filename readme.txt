=== Multifile Upload Field for Contact Form 7 ===
Contributors: spyrosvl,hoody_pl
Tags: contact, form, contact form, contact form 7 multiple files upload, 
Requires at least: 4.3
Tested up to: 4.7.4
Stable tag: 1.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Multiple files upload field addon for Contact Form 7

== Description ==

It adds multiple file upload capability to Contact Form 7. You may also attach the files to the outgoing email. You can also receive all attachments in one ZIP file. It requires ZipArchive() installed and enable in PHP.

== Installation ==

1. Upload the entire `multifile-for-contact-form-7` folder to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.

You will find the 'multifile' tag as you create your form.

== Frequently Asked Questions ==

1. Will it work with other form plugins except from CF7?
No

2. Can I get one ZIP file as attachment instead of separate files?
Yes, just add the "send_zip" attribute in your multifile tag or check the checkbox next to "Send ZIP archive" in the Form-tag Generator.

== Screenshots ==

1. screenshot-1.png

== Changelog ==

= 1.0.2 =

* Changed the "Accept wildcard /*" field from input to checkbox in the Form-tag Generator
* Added "Send ZIP archive" checkbox field in the Form-tag Generator to enable/disable ZIP archiving of attachments.
* Code formatting

= 1.0.1 =

* Added a filter on the frontend input field

= 1.0.0 =

* Initial release
