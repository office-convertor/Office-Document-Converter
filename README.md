Office Document Converter
=========================

[![Join the chat at https://gitter.im/chellem/Office-Document-Converter](https://badges.gitter.im/chellem/Office-Document-Converter.svg)](https://gitter.im/chellem/Office-Document-Converter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Overview
--------
Office Document Converter (ODC) is an online convertor for office document which runs as a web service. Its aim is to provide the facility of converting almost all office documents into image which make office documents viewable even without any office suite software installed on your machines.

Other services provided by ODC are listed below:
------------------------------------------------
- Convert to Portable Document Format (PDF)
- Virus Scanning on upload files
- Can optionally compressed the output (images or PDF)
- Allow different image format including jpeg, png, bmp - default: jpg
- Allow different resolution of images

List of files supported by ODC:
-------------------------------
- Word Processing format
	* Rich Text Format (rtf)
	* OpenDocument text (odt)
	* MS Word (doc,docx)
- Spreedsheet
	* OpenDocument Spreedsheet (ods)
	* MS Excel (xls,xlsx)
- Presentation
	- OpenDocument Presentation (odp)
	- MS Powerpoint (ppt,pptx)
- Portable Document Format (pdf)

Installation
-------------

Edit the config (`resources/config.php`) and the run application from the command below.

```php
php -S localhost:8000 -t .
```
