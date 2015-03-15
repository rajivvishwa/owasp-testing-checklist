# Introduction #

OWASP based Web Application Security Testing Checklist is an Excel based checklist which helps you to track the status of completed and pending test cases.

# Details #
This checklist is completely based on OWASP Testing Guide v 3. The OWASP Testing Guide includes a “best practice” penetration testing framework which users can implement in their own organizations and a “low level” penetration testing guide that describes techniques for testing most common web application and web service security issues.

The main intention of creating this checklist is to minimize our effort we would have put if we had to go through the 350 page OWASP Testing guide everytime during our testing.

I’ve added 66 test cases falling under different categories and you can add your own test by inserting a row in the Checklist and then changing the Overall status formulas.

## Quick Completion Status ##

This section gives the details on the total checks completed, vulnerabilities noticed so far, and overall status in percentage.

## Risk Metric Chart ##

Displays the number of High, Medium, Low and Info risk items. This can help us to give a quick glance on the ratio of High risk items.

**Note:** The Security Tester has to decide upon the rating of risk for each vulnerability. Check the OWASP Guide for more details

## Alerts Displayed ##

Alerts are displayed whenever there is some inconsistency with the task completion marked and the risk value updated.

Alert symbol (<font color='blue'>!!</font>**) is displayed when.
Status is marked as**<font color='green'>'Done'</font>**but Risk rating is not updated
Risk is marked but Status still shows**<font color='red'>'Not Done'</font>

## Features ##

  * Quick Status on completion of the tasks
  * Reference Sheet which contains short info on each test case
  * Risk Metric Chart displays the distribution of vulnerabilities based on the risk rating
  * Tiny alerts displayed if task is marked complete, but risk level is not mentioned (and vice versa)
  * List of tools to be used for various test cases (incomplete)