# SCMS Process & Resources

#### This is the process in which each course for SCMS is built - from storyboard to Pilot. This document will include each step of the process along with what resources are being utilized.

## Setup Process

**Before any work begins on a course, developers must first ensure that they have all the necessary programs.** This includes _NPM, GitHub, and a text editor of choice._ Once they have those, work can begin on each course. From here, we will break it down into steps.


## Steps

##### Step 1. Course Layout
--------------------------------
Once storyboards are final for the course, all the slides are mapped out into pages for the HTML documents. This is done to make it easier once the pages are actually built so we have an understanding of exactly how many files are needed, and what content will go on each file.

This is put into a spreadsheet which is also used to track progress, as well as track additional resources for the pages such as images, audio, and captions.

##### Step 2-A. Building the framework
---------------------------------------------
Once the pages have been mapped out, it's time to begin building the framework for the course. This starts with making a copy of the template that is setup for each course. This template includes all of the folders and files necessary to run the course, along with styles and metadata.

After creating the copy, a batch file is then created that will build out the files that were previously mapped out. Once those files are built, they are put into the course and it is pushed up to GitHub for developers to pull down onto their machines. The content from the storyboards is then placed onto the HTML files with a basic framework that can later be styled out

##### Step 2-B. Audio & Scripts
-------------------------------------
While the framework for the course is being created, work on audio usually begins at the same time. The storyboards contain scripts for the audio that will be put into the course. Those scripts are compiled into a document for the narrator, and are organized into what recording will go to which file.

Once the recording process is done, the audio is then cut, mastered, and output to a much smaller file to be put into the course. Once the audio is completed, whoever is working on it can then move on to the next step or help place the content.

##### Step 3. Styles & Interactions
------------------------------------------
Once the content has been placed, it's time to style the actual pages. Most of the styles are gathered from FLGGuide and are usually left to best judgement. Then come interactions. Interactions such as Tabs, Accordions, and reveals are common and usually come in various different forms and layouts. While there is an extensive library for these, sometimes there are some custom ones that are brand new. As for the new interactions and layouts, this is the time to start building them out with custom SCSS files. 

These files must be named appropriately so anyone can tell what they are. Documentation must also make sense to those not working on that interaction, which means that classes and variables must also be named appropriately.

##### Step 4. Images
------------------------
Every course has images for various pages and interactions. In order to satisfy the requests for specific images, we turn to Adobe Stock in order to find appropriate images. Stock images go into a folder where they will be cropped and sized appropriately for each different page layout. They are also exported as a much smaller file size for better loading times.

Once images have been sized and processed, they are exported with an appropriate file name that represents the actual contents of the image, given alt text, and placed into the pages.

##### Step 5. QA
-------------------
When everything has been completed, it's time for QA. QA will go through the course to look for issues with functionality, spelling errors, mismatched text, audio, captions, images, and (if time permits) 508 compliance. Once QA has gone through this process for each module,  developers can then fix these issues before the course is finalized and sent out.

## Documentation

Documentation is important in ensuring that every step of the process has been completed and that the team is on the same page as to where they are in the project.

##### Course Spreadsheet
----------------------------
As mentioned earlier, a spreadsheet is created to track the progress of each course, as well as map out what content will be on which page.
