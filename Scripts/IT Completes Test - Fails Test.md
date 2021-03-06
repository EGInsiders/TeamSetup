---
title: IT Contact completes IT testing Process - Fails Test
layout: post
author: eduguidepfl
permalink: /it-contact-completes-it-testing-process/
source-id: 1a-XuypRuLwnnFbmLXM7Pb-3ylmCbuvmdIUpDywe-mcM
published: true
---
# Coach requests IT Test

### Send Invitation

Given that I am viewing the IT Contact Invite Page
When I enter an email address into the field labeled "Add Email to Invite" {eduguidepfl+VarfolomeiValter@gmail.com}
And select a coach role
And click "Send Invite"
Then the invitation confirmation modal appears

###

### Confirm invitation				

Given that I am viewing the invitation confirmation modal
When I enter a custom message
And click "Send Invite"
Then the modal clears
And the system responds, "Your invitations have been processed and necessary emails sent out."

###

### User Responds to team invitation			

Given that the invitation arrives in my inbox
When I click on the link "Join [Team name] Now"
Then I am taken to the site
And asked "Do you have an account?"

###

### Decision Tree

Given that I am viewing the Decision Tree
And, the page says, "In order to process the invitation, you must first create an account or log into an existing account."
And the page asks, "Do you have an account?"
When I click, "No, Join"
Then I am taken to the registration form

###

### Register for an account

Given that I am on the registration form for IT Contacts
When I enter my first name
And Last Name
And Job Title
And Mobile Phone
And join code (pre-populated)
And Email address (pre-populated)
And confirm email address (pre-populated)
and Password
And Confirm Password (pre-populated)
And I click "Join"	


#/##



# IT Contact Completes IT Test Process


# IT Contact Responds To Welcome screen

Given that I am on the Welcome Page in the IT Test Wizard
When I click on "Get Started"
Then I am taken to the "Network" page

###

## IT Contact views Network window in IT Testing Wizard

When I click on "I've completed This"
Then I am taken to the System Page

###

## IT Contact views System Wizard Page

When I click on "Systems will meet these requirements"
Then I am taken to the Compatibility page

###

## IT Contact views Compatibility page

When I view the compatibility page
Then a checkmark or an x appears next to "Javascript Supported"
And "Cookies supported"
And "AJAX Supported"
And "HINCLUDE Supported"
And "All Tests have completed successfully"
And I am taken to the "Test" page when I click "Continue"

###

## IT Contact views the Test Page

When I click "Start Path"
Then I am taken to the IT Testing Path

###

# Test Path

## User advances to first activity in the path

Given that I have just uploaded a personal avatar
When I click the "Next" arrow
Then I am taken to the first activity in the path

###

# Testing EduGuide Path Functionality

## EduGuide Over the next few slides we're going to have you test some of the features in the system the students will be using. Please make sure you are testing on a typical device a student may use and the same network connection they will be using. 
If you are not, please exit the Path using the menu which can be opened with the icon to the top left and try again from an appropriate device. The purpose of this exercise is to make sure the students will be able to use the system as expected.

## EduGuide First let's test the comment functionality. In the comment field please enter some text and press return to save it. Once the comment has saved click the next button (right arrow) to continue. 
If you can not see the form, save a comment or see the next button, please let us know using the help system in the menu or by emailing web@eduguide.org.

Comments

## EduGuide Next we'll test that images display as expected. If the image in this slide does not load after a reasonable amount of time, please comment to let us know.

Image

## EduGuide Now we need to test that video playback works. Please try to play the video included on this slide.
If the video is not visible or playback fails, please comment here to let us know what happened.

Video

## EduGuide This is an essay step typically used for longer answers. 
Please enter some text into the field, click save, then click the next button.

Essay Step

## EduGuide On this step you should see either see a PDF file displayed in place or a link to view the file. 
If you do not see either of these, please add a comment to let us know.

Display Document/PDF

## Thanks for running through this quick test for us

When I click that the test passed
Then I am shown the message, "Thank you for running this test for us."
