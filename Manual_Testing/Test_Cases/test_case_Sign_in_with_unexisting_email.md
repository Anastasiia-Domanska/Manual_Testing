# QTTA-16

## Sign in with unexisting email
Authorization controller

Pre-conditions
Navigate to the sign in page http://localhost:5173/#/login

## Steps

  1. Enter unexisting email in the email field

     Input data
     user99@example.com

     Expected result
     email entered

  2. Enter valid password

     Input data
     Qwerty123!

     Expected result
     password entered

  3. Click on hte Sign in button

     Expected result
     shows an error that the user with those email is not registered

Test suite: Authorization controller
Severity: Normal
Status: Actual
Priority: Medium
Behavior: Negative
Type: Functional
Automation status: Manual

Created by Anastasiia Domanska