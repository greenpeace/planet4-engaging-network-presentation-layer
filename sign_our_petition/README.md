# Engaging Network Petition form setup steps

Below steps helps you to setup petition form on Engaging Network plateform.

## header and footer template setup in EN plateform

Create new template in EN using below 2 files -
- header.html
- footer.html

## EN Form block setup (Page 1)

Steps :
* Select Add row >> **One column** structure
* From Components, drag **Code block** in **One column** structure
* In that **Code block** copy the content of ```sign-our-petition-top-code-block.html``` file
* From Forms, drag **Form block**
	- In form block select First name, Last name, Email, Country and optin checkbox and submit button fields
	- In Form block >> **Form block styling**, add **Custom class names** as **petition-form**
* Again from Components, drag Code block below to **Form block** and copy the content from ```sign-our-petition-bottom-code-block.html```

## EN Form Thank you page setup (Page 2)

Steps :
* Select Add row >> **One column** structure
* From Components, drag **Code block** in **One column** structure
* In that **Code block** copy the content of ```thank-you-top-code-block.html``` file
* From **Social details**, drag **Share buttons**
* Again from Components, drag Code block below to **Share buttons** and copy the content from ```thank-you-bottom-code-block.html```

### How to edit background image on petition page?

To use image on EN plateform, we have 2 options.
1. Use image link
2. Upload image on EN plateform using **Image block**(Just to copy Image path to use further)

In ```sign-our-petition-top-code-block.html``` file edit below code to update petition backgraund image. The recommended backgraund image dimensions are 2000 pixels (width) by 2000 pixels (height).

```
    <div class="page-header-background">
      <!--Add page background img here-->
      <img src="https://aaf1a18515da0e792f78-c27fdabe952dfc357fe25ebf5c8897ee.ssl.cf5.rackcdn.com/1735/sign-petition-header_small.jpg?v=1515405191000" class="page-header-image" />
    </div>
```

### How to edit background image on Thank you page?

In ```thank-you-top-code-block.html``` file edit below code to update Thank you page backgraund image.

```
    <div class="page-header-background">
      <!--Add page background img here-->
      <img src="https://aaf1a18515da0e792f78-c27fdabe952dfc357fe25ebf5c8897ee.ssl.cf5.rackcdn.com/1735/sign-petition-header_small.jpg?v=1515405191000" class="page-header-image" />
    </div>
```

### How to update page header and footer links?

Editor can update header and footer menu links from ```footer.html``` file.

```
/* Configure Planet4 page links here*/
/*Header links*/
var p4_site_url          = "https://www.greenpeace.org/international/";
var p4_site_act_page     = "https://www.greenpeace.org/international/act/";
var p4_site_explore_page = "https://www.greenpeace.org/international/explore/";
var p4_site_donate_btn   = "https://secured.greenpeace.org/international/en/supportus/?_ga=2.256767427.937523877.1515410303-280997801.1515410303";

/*Footer links*/
var p4_fb_page        = "https://www.facebook.com/greenpeace.international";
var p4_twitter_page   = "https://www.twitter.com/greenpeace";
var p4_yt_page        = "https://www.youtube.com/greenpeace";
var p4_instagram_page = "https://www.instagram.com/greenpeace/";
var p4_site_news_page  = "https://www.greenpeace.org/international/?s=+&orderby=relevant&f%5Bctype%5D%5BPost%5D=3";
var p4_site_about_page = "https://www.greenpeace.org/international/explore/about/";
var p4_site_jobs_page  = "https://www.linkedin.com/jobs/greenpeace-jobs/";
var p4_site_press_page = "https://www.greenpeace.org/international/press-centre/";
var p4_site_privacy_page     = "https://www.greenpeace.org/international/privacy/";
var p4_community_policy_page = "https://www.greenpeace.org/international/community-policy/";
var p4_search_archive_page   = "http://www.greenpeace.org/international/en/System-templates/Search-results/?adv=true&_ga=2.259297730.937523877.1515410303-280997801.1515410303";
```