---
title: Securing Your Account
group: getting-started
---

Two-factor Authentication (TFA) is an added layer of security to better protect your Magento.com account from unauthorized users who might want to use your account in ways you do not want.  Two-factor authentication achieves this by requiring a "second factor" (beyond your standard username and password combination) in order to complete the login process.  This second factor takes the form of special, temporary verification codes that are continuously generated by a two-factor authentication application (on your mobile phone, for example) that is synced to your Magento.com user account.  With two-factor authentication enabled, an unauthorized user must have your username and password combination (first factor) as well as have access to the two-factor authentication application on your personal device (second factor) in order to log into your Magento.com account - which is much more difficult and, therefore, secure.

## Before you begin:

In order to use two-factor authentication, you must have a two-factor authentication application.

1. Download and install a two-factor authentication app on your personal device (e.g. smartphone, tablet, computer); there are many to choose from, but some popular free options include:

   - Google Authenticator (iOS, Android, Blackberry)

   - Authy (iOS, Android)

   - Microsoft Authenticator (iOS, Android, Windows Phone)

## To enable two-factor authentication:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click on <span class="btn"> Account Settings </span> in the left navigation pane.

1. Click on <span class="btn"> Two-factor Authentication </span> under the Account Settings menu within the left navigation pane.

   ![]({% link images/images/magento-account-2fa-enable.png %}){: .zoom}
   _Enable 2FA_

1. Click <span class="btn"> Enable </span> to begin the two-factor authentication setup process.

1. Re-enter your password and click <span class="btn"> Verify Password </span> to continue.

   ![]({% link images/images/magento-account-2fa-enable-verify-password.png %}){: .zoom}
   _Verify password_

1. Open the two-factor authentication application you downloaded and installed on your personal device.

1. Enter the **Setup Code** into your two-factor authentication application by either scanning the QR code using the two-factor authentication application or manually typing the **Setup Code** into your two-factor authentication application; this will sync your two-factor authentication application with your Magento.com account and allow your two-factor authentication application to generate verification codes that Magento.com will accept.

   - Note: **Verification Codes** are constantly expiring and re-generated by your two-factor authentication application for security purposes, so always use the one that is currently displayed.

1. With your two-factor authentication application now synced to your Magento.com account, enter the **Verification Code** displayed in your two-factor authentication application and click <span class="btn"> Verify Code </span> to continue.

   ![]({% link images/images/magento-account-2fa-enable-setup-app.png %}){: .zoom}
   _Setup 2FA app_

1. Save the **Recovery Codes** presented in a safe and accessible place; in the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a **Recovery Code** is the only way to regain access to your Magento.com account.

   - Each **Recovery Code** is one-time use only, so do not try to re-use a **Recovery Code** you have already used previously (but you can always generate more, see below for details).

   - **Recovery Codes** are case-sensitive.

1. Once you have successfully saved your **Recovery Codes**, check the checkbox to confirm and click <span class="btn"> Submit </span> to continue.

   ![]({% link images/images/magento-account-2fa-store-recovery-codes.png %}){: .zoom}
   _Store recovery codes_

1. Enter a **Recovery Email** to help ensure that you can recover access to your account in the event that you cannot generate a **Verification Code** from your two-factor authentication application and you do not have access to an unused pre-generated **Recovery Code**.  

   - Once every 24 hours, you will be able to generate and send a temporary Recovery Code to your designated Recovery Email address which you can use to regain access to your account.

   - It is imperative that you maintain access to the email account of your Recovery Email; otherwise, you will not be able to access any temporary Recovery Codes sent to that account.

   ![]({% link images/images/magento-account-2fa-set-recovery-email.png %}){: .zoom}
   _Set recovery email_

1. Once you have entered your **Recovery Email** address, check the checkbox to confirm and click <span class="btn"> Submit </span> to complete the two-factor authentication setup process.

   - An email notification will be sent to the email address associated with your Magento.com to confirm that you have successfully enabled two-factor authentication.

   - An email notification will be sent to the **Recovery Email** you designated to confirm that particular email address is on file as your **Recovery Email** for receiving a temporary **Recovery Code**.

## To log in to your Magento.com account using a verification code:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Enter the **Verification Code** displayed in your two-factor authentication application when prompted.

   ![]({% link images/images/magento-account-2fa-login-verification-code.png %}){: .zoom}
   _Enter verification code_

1. Click <span class="btn"> Submit </span> to complete the login process.

## To log in to your Magento.com account using a recovery code:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click <span class="btn"> Use recovery code </span> to bypass the verification code prompt.

   ![]({% link images/images/magento-account-2fa-login-verification-code.png %}){: .zoom}
   _Enter verification code_

1. Enter an unused **Recovery Code** when prompted.

   ![]({% link images/images/magento-account-2fa-login-recovery-code.png %}){: .zoom}
   _Enter recovery code_

1. Click <span class="btn"> Submit </span> to complete the login process.

## To log in to your Magento.com account using your recovery email:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click <span class="btn"> Use recovery code </span> to bypass the verification code prompt.

   ![]({% link images/images/magento-account-2fa-login-verification-code.png %}){: .zoom}
   _Use recovery code_

1. Click on the <span class="btn"> recovery email </span> hyperlink to have a temporary **Recovery Code** sent to the Recovery Email address on file for your Magento.com account.

   ![]({% link images/images/magento-account-2fa-login-recovery-email.png %}){: .zoom}
   _Use recovery email_

1. Access the email account of your **Recovery Email** to retrieve the temporary **Recovery Code** and enter it into the designated fields.

1. Click <span class="btn"> Submit </span> to complete the login process.

   - Since the Recovery Email capability is only available once every 24 hours, it is strongly recommended that you generate new Recovery Codes and securely store them to avoid any future issues with accessing your Magento.com account. 

   - It is also strongly recommended that you change your two-factor authentication application (if you have a device available) to able to generate Verification Codes again and use them to access your Magento.com account.

## To view your recovery codes:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.  Complete the login process using one of the two-factor authentication methods above.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click on <span class="btn"> Account Settings </span> in the left navigation pane.

1. Click on <span class="btn"> Two-factor Authentication </span> under the Account Settings menu within the left navigation pane.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _2FA settings_

1. Click <span class="btn"> View Recovery Codes </span> to view your pre-generated **Recovery Codes**.

1. Re-enter your password and click <span class="btn"> Verify Password </span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Save the **Recovery Codes** presented in a safe and accessible place; in the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a **Recovery Code** is the only way to regain access to your Magento.com account.

   - Each **Recovery Code** is one-time use only, so do not try to re-use a Recovery Code you have already used previously (but you can always generate more, see below for details).

   - **Recovery Codes** are case-sensitive.

   ![]({% link images/images/magento-account-2fa-view-recovery-codes.png %}){: .zoom}
   _View recovery codes_

1. Once you have successfully saved your **Recovery Codes**, check the checkbox to confirm and click <span class="btn"> Submit </span> to dismiss the dialog box.

## To generate new recovery codes:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.  Complete the login process using one of the two-factor authentication methods above.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click on <span class="btn"> Account Settings </span> in the left navigation pane.

1. Click on <span class="btn"> Two-factor Authentication </span> under the Account Settings menu within the left navigation pane.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _2FA settings_

1. Click <span class="btn"> Generate New Recovery Codes </span> to generate new pre-generated **Recovery Codes**.

1. Re-enter your password and click <span class="btn"> Verify Password </span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Save the **Recovery Codes** presented in a safe and accessible place; in the event that you cannot provide a **Verification Code** to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a Recovery Code is the only way to regain access to your Magento.com account.

   - All previously generated **Recovery Codes** are now rendered invalid and should be discarded (only the current set of generated **Recovery Codes** will work).

   - **Recovery Codes** are case-sensitive.

   ![]({% link images/images/magento-account-2fa-generate-recovery-codes.png %}){: .zoom}
   _Generate recovery codes_

1. Once you have successfully saved your **Recovery Codes**, check the checkbox to confirm and click <span class="btn"> Submit </span> to dismiss the dialog box.

## To change your recovery email:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.  Complete the login process using one of the two-factor authentication methods above.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click on <span class="btn"> Account Settings </span> in the left navigation pane.

1. Click on <span class="btn"> Two-factor Authentication </span> under the Account Settings menu within the left navigation pane.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _2FA settings_

1. Click <span class="btn"> Change Recovery Email </span> to change the **Recovery Email** on file for your account.

1. Re-enter your password and click <span class="btn"> Verify Password </span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_
   
1. Enter a **Recovery Email** to help ensure that you can recover access to your account in the event that you cannot generate a **Verification Code** from your two-factor authentication application and you do not have access to an unused pre-generated **Recovery Code**.  

   - Once every 24 hours, you will be able to generate and send a temporary Recovery Code to your designated Recovery Email address which you can use to regain access to your account.

   - It is imperative that you maintain access to the email account of your Recovery Email; otherwise, you will not be able to access any temporary Recovery Codes sent to that account.

   ![]({% link images/images/magento-account-2fa-set-recovery-email.png %}){: .zoom}
   _Set recovery email_

1. Once you have entered your **Recovery Email** address, check the checkbox to confirm and click <span class="btn"> Submit </span> to dismiss the dialog box.

   - An email notification will be sent to the **Recovery Email** you designated to confirm that particular email address is on file as your **Recovery Email** for receiving temporary **Recovery Codes**.

## To change your two-factor authentication application:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.  Complete the login process using one of the two-factor authentication methods above.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click on <span class="btn"> Account Settings </span> in the left navigation pane.

1. Click on <span class="btn"> Two-factor Authentication </span> under the Account Settings menu within the left navigation pane.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _2FA settings_

1. Click <span class="btn"> Change TFA Application </span> to use a different two-factor authentication application with your Magento.com account.

1. Re-enter your password and click <span class="btn"> Verify Password </span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Open the two-factor authentication application you downloaded and installed on your personal device.

1. Enter the **Setup Code** into your two-factor authentication application by either scanning the QR code using the two-factor authentication application or manually typing the **Setup Code** into your two-factor authentication application; this will sync your two-factor authentication application with your Magento.com account and allow your two-factor authentication application to generate verification codes that Magento.com will accept.

   - Note: **Verification Codes** are constantly expiring and re-generated by your two-factor authentication application for security purposes, so always use the one that is currently displayed.

1. With your two-factor authentication application now synced to your Magento.com account, enter the **Verification Code** displayed in your two-factor authentication application and click <span class="btn"> Verify Code </span> to continue.

   ![]({% link images/images/magento-account-2fa-enable-setup-app.png %}){: .zoom}
   _Setup 2FA app_

1. Save the **Recovery Codes** presented in a safe and accessible place; in the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a **Recovery Code** is the only way to regain access to your Magento.com account.

   - Each **Recovery Code** is one-time use only, so do not try to re-use a **Recovery Code** you have already used previously (but you can always generate more, see below for details).

   - **Recovery Codes** are case-sensitive.

1. Once you have successfully saved your **Recovery Codes**, check the checkbox to confirm and click <span class="btn"> Submit </span> to continue.

   ![]({% link images/images/magento-account-2fa-store-recovery-codes.png %}){: .zoom}
   _Store recovery codes_

1. Enter a **Recovery Email** to help ensure that you can recover access to your account in the event that you cannot generate a **Verification Code** from your two-factor authentication application and you do not have access to an unused pre-generated **Recovery Code**.  

   - Once every 24 hours, you will be able to generate and send a temporary Recovery Code to your designated Recovery Email address which you can use to regain access to your account.

   - It is imperative that you maintain access to the email account of your Recovery Email; otherwise, you will not be able to access any temporary Recovery Codes sent to that account.

   ![]({% link images/images/magento-account-2fa-set-recovery-email.png %}){: .zoom}
   _Set recovery email_

1. Once you have entered your **Recovery Email** address, check the checkbox to confirm and click <span class="btn"> Submit </span> to complete the two-factor authentication setup process.

   - An email notification will be sent to the **Recovery Email** you designated to confirm that particular email address is on file as your **Recovery Email** for receiving a temporary **Recovery Code**.

## To disable two-factor authentication:

1. Go to **My Account** at: **[https://account.magento.com/customer/account/login][1]{:target="_blank"}**

1. Enter your username and password combination and click <span class="btn"> Login </span> to log into My Account.  Complete the login process using one of the two-factor authentication methods above.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click on <span class="btn"> Account Settings </span> in the left navigation pane.

1. Click on <span class="btn"> Two-factor Authentication </span> under the Account Settings menu within the left navigation pane.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _2FA settings_

1. Click <span class="btn"> Disable </span> to begin the two-factor authentication deactivation process.

1. Re-enter your password and click <span class="btn"> Verify Password </span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Check the checkbox to confirm and click <span class="btn"> Submit </span> to complete the deactivation for two-factor authentication; you will also receive an email confirmation indicating that two-factor authentication has been disabled on your Magento.com account.

   ![]({% link images/images/magento-account-2fa-disable-confirmation.png %}){: .zoom}
   _Disable 2FA_

[1]: http://go.magento.com/
[2]: https://community.magento.com/