The website of YPKBK, including a very simple CMS

# Application structure
/ - the site
/admin - the administration
/api - the api for the application

The root application simply returns the public static site. In the templates returned will call back to the /api and get the content for the different parts of the page.

In the administration part we simply administer the small content chunks

# Kanban
## Later
* Google Analytics setup
* The Yayasan Pelayan Kesehatan Bala Keselamatan needs to be smaller for medium sized screens
* Link directly to hospital/clinic/news doesnt work


## Todo
* Set up github
	* Deny
	* Org for YPKBK
* Background pictures
	* header image

* Administration Clinics
* Administration Lain-lain
* Administration Blog

* Use hospital data on the site
* Use clinic data on the site
* Use lain-lain texts on the site
* Use blog data on the site

## Fix

## Doing (2)
* make favicon for ypkbk


## Done
* closing modal windows should set URL (ex. #institution-rsbungsu -> #hospitals)
* Admin hospitals
* Fixed... again the linking to the to modal windows
* Background image for contact us
* Hardcoded example news section
* Make the social media icons bigger using fa-2x
* The panels for hospital doesn't have to be in <div class="row"></div> they will just overflow to the next line
* Structure the application using mount
	* Admin
	* Api

* Hardcoded, example clinic data
	* Define information
	** Opsir
	** Visi Misi
	** Pelayanan
	** Rujukan
	* Good pictures (400 x 250)
	* Information
* For example hospital
** pictures for web, fb and emails
** find good picture (400 wide x 250 high)
** get information to put on hospital page
* define hospital information
* Use CDN for common files
* Deploy first version


# License
The [MIT LICENSE](LICENSE) for the site code

Using the [Agency - Start Bootstrap Theme](http://startbootstrap.com/template-overviews/agency/) from [Start Bootstrap](http://startbootstrap.com) under the [Apache License](/public/LICENSE)