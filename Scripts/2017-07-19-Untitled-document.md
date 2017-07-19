---
title: # Launching a New Path Team
layout: post
author: eduguidepfl
permalink: /untitled-document/
source-id: 1H9qx8fT7c6rxnEph4uydVgumA_u7leh-zxz4Dt2tL2g
published: true
---
# Launching a New Path Team

## Navigate to Team launch Tool from Main Menu

Given that I am logged in as an admin

When I click on "Admin" in the main menu

And "Create partner team"

Then I am taken to the Partner Team creation wizard

## Complete the Set Up New Partner Team Wizard

### Organization Name

When I enter an organization name {Moonbase 7}

And click "Create Team"

Then I am taken to the "Path" screen

### Path

When I enter in "Medium" for the minimum number of words required

And "1" for Max new activities per day

And "on" for Enabled

And "Core Learning" for Path

And "20" for Max Activities for Subscription Period

And "July 1, 2017" for Subscription Start Date

And "June 30, 2018" for Subscription End Date

And "Off" for Literacy Tools

And "Off" for Audio Reader

And click "Save"

Then I am taken to the "Invite" page

### Send Invitation

When I enter an email address into the field

And click "Send Invite"

Then I am taken to the team

And the system responds, "An invitation email was sent to {recipient's email}. Once they accept their invitation they will be able to begin the team setup process."

