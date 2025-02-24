---
layout: fluid/pro_docs_base
category: pro-package
id: pro-native-builds
title: Keystores and Profiles - Ionic Pro Documentation
body_class: 'pro-docs'
hide_header_search: true
dark_header: true
---

# Keystores and Provisioning Profiles

Security Profiles securely store your credentials so you can easily reference
them when building your app in the cloud.

## Generating Credentials

You'll need two sets of Apple certificates when your app goes to production,
which means you'll eventually need two Security Profiles: one for development
and one for production.

We'll guide you through creating a development profile with the credentials
that you need for the desired platform below.

* [Android credentials](/docs/pro/package/android.html)
* [iOS credentials](/docs/pro/package/ios.html)

## Creating Security Profiles

After you have generated your Security Profile, you must upload it to Ionic Pro. Navigate to your App, then click on Package Tab and choose Certificates on the left hand side.

Click the **Add Profile** button to create a new Profile. Both iOS and Android certifications can be used with one Profile, so we recommend making things like "Real App Store Profile", etc.

Once that Profile has been created, click the **Edit** button for it and upload your iOS and Android certs.
