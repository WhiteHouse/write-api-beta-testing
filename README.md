### Contents

- [Welcome](#welcome)
  - [About We the People](#about-we-the-people)
  - [Request a key](#request-a-key)
  - [Our objectives for the beta period](#our-objectives-for-the-beta-period)
- [Getting started](#getting-started)
  - [API documentation and examples](#api-documentation-and-examples)
  - [Get involved](#get-involved)
  - [Feedback](#feedback)
- [Terms of Use](#terms-of-use)
- [Privacy](#privacy)

Welcome!
========

We're excited to work with you on the new Write API for the White House's [We
the People](http://petitions.whitehouse.gov) app! This GitHub repo is for beta
testers with API keys. It includes information about how to apply for a key,
tips for getting started with development. Please use the issue queue to share work
and ideas with other developers and to provide feedback to White House
developers on how we can make this API useful and easy to work with.


### About We the People

We the People is the White House's petitions platform -- giving people a new way to petition the government. The way it works is pretty simple: People can create or sign petitions on WhiteHouse.gov. If it gets enough support (i.e. signatures), it will receive an official response. And with more than 13 million users, it's been a big success.

So why the API? We know that even more people want to reach us on other sites
across the Internet. The Write API will allow individuals and organizations to
collect signatures from their own platforms (websites, native mobile apps, etc.)
and submit them to We the People, all without requiring users to visit our site.

### Request a key

Request early access to the We the People API here:
http://www.whitehouse.gov/webform/apply-we-people-write-api-beta

We are currently prioritizing requests from people and organizations who (1)
are able to produce a working proof-of-concept app before the [National Day of
Civic Hacking](http://hackforchange.org/) at the end of May, (2) are able to
attend a hack day / demo day at the White House complex on May 30, 2014, and (3)
will be able to "go live" with their apps as soon as the We the People API is
released publicly (sometime between May 30 and this fall).

### Our objectives for the beta period

- Test the Write API
- Fix issues and squash bugs
- Improve documentation ahead of a public release

As you build and code against the API, we hope you'll use this repo as a space to open issues, ask questions, and (if you'd like) coordinate with other participants.

If you'd like to form groups to work on a shared project, or post code here for
other participants to reuse, please feel free to use this repo as a shared sandbox.

Getting started
---------------

When your [request for an API key](#request-a-key) is approved, you will receive
an email including:

  - An API key enablind you to POST signatures to
    http://11111011100.api.whitehouse.gov/v1/signatures
  - A petition ID for a petition with no signatures (test POSTing signatures to
    this petition)
  - A petition ID for a petition that has met the response threshold
  - A petition ID for an expired petition
  
These IDs are unique to each beta tester. This should give you everything you
need to exercise the full read and write functionality of the API.

**Please note:**

- All API requests during the Beta period should go through
  http://11111011100.api.whitehouse.gov/ (this is a staging site with dummy
  data, you are not posting signatures to real petitions when you make API
  requests here)
- Use 'http, not 'https' during the Beta, but you'll need to use 'https' after
  this goes into production.
- For beta petitions, the threshold for a petition to be publicly visible is 2
  signatures, and the threshold for a "response" is 10 signatures (these equate
  to the current signature thresholds of 150 and 100,000 in production).

**Beta rules of the road:**

- During the beta period API keys are limited to 50,000 write calls (signatures)
  per month.
- API keys provided for the beta period are for use solely during the beta
  period, are not transferable, and are not to be shared.
- During the beta period, applications using API keys must not be released for
  use by the general public or used in a production environment.
- We the People API keys provided for the beta period may only be used to submit
  signatures to "sandbox" petitions created by the White House for the purpose
  of testing the API's functionality. Please do not create new petitions.
- Violation of these terms, or any of Petitions API Terms of Use may result in
  your API key being deactivated.

### API documentation and examples

- Staging: https://11111011100.petitions.whitehouse.gov/developers
- Production: https://petitions.whitehouse.gov/developers
- Examples: https://petitions.whitehouse.gov/how-why/api-gallery

### Get involved

If you're working on something, and you're interested in connecting with other
people working on things, please introduce yourself here:
https://github.com/WhiteHouse/write-api-beta-testing/issues/1.

### Feedback

Please send us feedback!

- [Issue queue for questions, bug reports, misc feedback about the API](https://github.com/WhiteHouse/write-api-beta-testing/issues)
- Update this documentation or share samples with the user community by
  forking this repo and submitting pull requests
  [here](https://github.com/WhiteHouse/write-api-beta-testing/pulls)
- Other developer feedback is welcome here:
  http://www.whitehouse.gov/developers/feedback


Terms of Use
------------

By participating in the beta period for Version 2.0 of the We the People API, you acknowledge that you have read, understood, and agree to be bound by these Terms of Use, as well as the terms and conditions contained in the WhiteHouse.gov Privacy Policy and the We the People’s Terms of Participation and Moderation Policy, and to comply with all applicable laws and regulations.

The purpose of the beta period is to test the We the People API's write methods, identify bugs and other technical issues, and develop tools that will allow others to submit signatures to We the People petitions platform without directing users to WhiteHouse.gov.

Participants in the beta period must provide or contribute to the development of constituent relationship management (CRM) systems that feature online petitions functionality. By taking part, you commit to develop against the API during the beta period and provide ongoing feedback to the White House team.

We the People API keys provided for the beta period are for use solely during the beta period, are not transferable, and are not to be shared. During the beta period, applications using API keys must not be released for use by the general public or used in a production environment. We the People API keys provided for the beta period may only be used to submit signatures to "sandbox" petitions created by the White House for the purpose of testing the API's functionality. Violation of these terms may result in your API key being deactivated.

Participation in the beta period does not constitute an endorsement of the participants' project or create a business relationship between the participant and the White House. The White House reserves the right to invite additional applicants to participate in the beta period on an ongoing basis should circumstances permit. The White House also reserve the right to scale back, cancel or suspend the beta period or individual API keys if necessary based on system stability or other technical issues that may arise during the beta period.

While the White House intends to release write methods for the We the People API, it is not obligated to do so. New terms of use for the API and new API keys would accompany such a release. The White House cannot guarantee that functionality developed during the beta period will be compliant with those terms of use.


Privacy
-------

This repo is associated with the official White House GitHub profile. All comments, messages, commits, and other submissions received through official White House pages including this GitHub page are subject to the Presidential Records Act and may be archived. Learn more: [WhiteHouse.gov/Privacy](http://WhiteHouse.gov/privacy)
