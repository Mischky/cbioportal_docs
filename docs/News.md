
# News

## README

* Data in portal represents cases signed-out as of June 30th, 2019 and includes mutation, copy number and fusion data. For more information, please refer to the [FAQs](https://cbioportal.ucsf.edu/cbioportal/faq) page ("What data types are in the portal?"). 
  * We will be doing approximately monthly DATA updates initially
* Report-derived pathogenicity annotations are not yet displayed in portal 
* There are several known bugs we have reported to the cBioPortal development team:
  * You cannot query for genes from the study summary view page; only from the Query tab of the homepage.
  * **H3F3A variants are showing up as H3F3B variants in portal!!** We have reported this issue to the cBioPortal development team and a fix is on the way shortly!
  * Some fusions are not showing up in the portal; we are in the process of investigating the source cause of this.
* Primary site
  * This is derived directly from the UCSF500 report and actually represents the source location of the biopsy; therefore it might not represent the true primary site of the tumor per se. We are working on obtaining the true primary site for cases in the portal.

## August 12, 2019
Version 1.0 of UCSF cBioPortal released to UCSF community!

*  Version of **data** is 1.0

* Version of **UI** is 1.18.1

### Coming Soon…

#### Content Enhancements

* Discrete copy number status

* Vital status

* Including the manually-assigned pathogenicity annotations in portal

#### Functionality Enhancements

Upgrade to UI version v3.0.4

* Genome Aggregation Database (gnomAD) population frequencies in the mutations table - see [example](http://bit.ly/2ISHgiu):

 ![gnomad feature news](https://user-images.githubusercontent.com/1334004/59794400-e07c9c00-92a6-11e9-97ea-a79bfc8f3885.gif)

* Group Comparison Feature: Compare clinical and genomic features of user-defined groups of samples/patients. [View Tutorial](https://www.cbioportal.org/tutorials#group-comparison)

![group-comparison](https://user-images.githubusercontent.com/840895/59052073-40f9eb00-885c-11e9-9ddb-6d036533e5f5.png)

* Use the new quick search tab on the homepage to more easily navigate to a study, gene or patient:

 ![quick_search_news](https://user-images.githubusercontent.com/1334004/55113078-8f4c7a00-50b4-11e9-9d95-e9a6e1dcda52.gif)

* Bookmarking or sharing your selected samples as virtual studies with the _share_ icon on the study summary page. [Example: a virtual study of breast tumors](https://www.cbioportal.org/study?id=5a12fd57498eb8b3d5605cd4)
