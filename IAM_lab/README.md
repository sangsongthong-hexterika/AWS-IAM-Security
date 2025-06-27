# AWS IAM Lab

## Overview

This was how I learned about AWS IAM by setting up the root account and created other accounts with different detail. The overview idea is to start off by setting up the root account. Then, set other accounts with slight variation such as adding it to Administrator Access group or not adding it there or set a password vs passwordless.

## Creating Root Account & Post Initial Setup

This account is the first account that the owner of the company or an AWS user needs to create in order to use the services unless they are the user at a company who only need to sign-in to work as a normal user. Basically, whoever creates and/or have accessed to this account is the most powerful person who can control the AWS usage of the whole company. This person is also responsible to manage the billing of the services. This account isn't a day-to-day account.

Basically in this step, I start from signing up for the root account. The log in as the root account. Then setup the MFA and billing. ***Talk about the how to with screenshots***

The tasks that can only be performed by the root account.

+ Manage Billing - Only the root account can manage the billing. However, the root account can grant other IAM account the right to view the billing with the ***Read-Only*** privilege.
+ Create other IAM accounts
+ Delete other IAM accounts
+ Create Groups & Policies

Special groups & policies that needs to be created by the root account.

## Things That An IAM Account With AdministratorAccess Can And Cannot Do

## Create AdministratorAccess Group Policy (Need To Be Done From Root Account)

## Create A Group With The Policy That Grant The Accounts ***READ-ONLY*** To View The Billing But Not Managing

## Creating An IAM Account With Password

I start of by *explain the how to*.

The benefit of creating a password for this account.

The risk of creating a password for this account.

Best Practice.

+ The admin setup with default a password and force password reset on the user at their initial login.
+ Secure password policy needs to be applied. This means the admin should care enough about enforcing password strength best practice.
  + 8-14 characters long
  + At least 1 uppercase
  + At least 1 lowercase
  + At least 1 number
  + At least 1 symbol
  + Decide whether to allow blank space or not

## Creating a Passwordless IAM Account

I start of by *explain the how to*.

The benefit of ***NOT*** creating a password for this account.

The cons of ***NOT*** creating a password for this account.

Best Practice.
