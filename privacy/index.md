# Privacy Policy — BeforeYouTrust

**Effective date:** 2026-10-10  
**Operator:** Digital Pulse d.o.o.  
**Contact:** [hello@digitalpulsedoo.com](mailto:hello@digitalpulsedoo.com)  
**Published policy URL:** https://beforeyoutrust.github.io/BeforeYouTrust/privacy/

---

## Summary

BeforeYouTrust does not require an account and does not include advertising,
tracking, or analytics SDKs. It stores certain information locally on your
device so the app can work. When you choose to run a message check after giving
the in-app consent, the text you chose to review is sent to TypeSafe's service
through `api.typesafe.pro` for analysis. Screenshots are converted to text on
your device and the image itself is not sent for analysis.

Please do not submit passwords, card numbers, authentication codes, government
identifiers, private health information, or other sensitive information unless
you are authorised to share it and accept this processing.

## Who is responsible

Digital Pulse d.o.o. is responsible for the processing described in this
policy. Contact us at [hello@digitalpulsedoo.com](mailto:hello@digitalpulsedoo.com)
with questions or requests about privacy.

## Information stored on your device

The app keeps the following information on the device where you use it:

- your current message draft and its input source, for up to 24 hours;
- your consent choice, language and appearance preferences, and whether history
  saving is enabled;
- saved check results and their quoted evidence in local history, for up to 30
  days when history is enabled (history is enabled by default); and
- content you explicitly share through the Share Extension, including a shared
  image while it is waiting for you to import or discard it. Pending shared
  items expire after up to 24 hours.

Drafts and history are local to your device. The app does not use an app account
or CloudKit to synchronise them, and its sensitive local files are marked to be
excluded from device backup. Local data can be removed using the history and
draft controls in the app, by disabling or clearing history, by discarding a
shared import, or by deleting the app and its data. iOS and your device backup
settings may affect other app preferences or system-level copies outside the
app's control.

## Screenshots, OCR and sharing

If you choose a screenshot or share one to BeforeYouTrust, text recognition
uses Apple's on-device Vision framework. The app sends the recognised text only
when you later tap **Check message** and have given consent. It does not upload
the original image to TypeSafe for analysis. A shared image may be held locally
while you decide whether to import it; it is not kept in history.

The Share Extension does not start an analysis by itself. Links are read as
text only: the app does not open, visit, resolve, or check the reputation of a
link.

## What is sent when you run a check

After you give the specific in-app consent and select **Check message**, the
app sends the text you are reviewing and short excerpts derived from that text
to `https://api.typesafe.pro/v1/systemone`. The analysis uses TypeSafe's Jev
service to return typed risk judgments and evidence selections.

The app does not send an account name, login, device identifier, local history,
consent record, original screenshot, or the image's bytes as part of this
request. As with any internet service, TypeSafe and network providers can
receive connection information such as your IP address, request time, and
technical information needed to operate and secure the service.

The app communicates directly with this service; it does not operate its own
analysis server or transmit message content to Digital Pulse d.o.o.'s separate
backend. A request already received by a provider cannot be withdrawn by
cancelling the app's display of the result or clearing local app data.

## Why we process it

We process the text you voluntarily submit to provide the message-review result
you request. We process local settings, drafts and history to provide the app's
features. If you email us, we use your email address and message to answer and
resolve your request.

Where applicable, our legal basis is performance of the service you request;
we may also process limited information for our legitimate interests in running,
securing, and supporting the app, and where required to meet a legal obligation.
The app does not sell personal information or use it for targeted advertising.

BeforeYouTrust is a decision-support tool, not a sender-verification, fraud
investigation, credit, employment, insurance, or other automated decision
service. Its output is not a guarantee and does not make decisions with legal
or similarly significant effects about you.

## TypeSafe and international processing

TypeSafe AI, Inc. processes submitted text to provide the analysis. Its
published policy states that it does not train or fine-tune AI or machine
learning models on submitted inputs. It also states that it may process input,
technical information, and service telemetry to provide, secure, and operate
its services, and that its services are hosted in the United States. Its policy
does not provide a fixed retention period for every API request; do not treat
the app as a zero-retention service.

Read [TypeSafe's Privacy Policy](https://typesafe.ai/legal/privacy-policy),
[Master Customer Agreement](https://typesafe.ai/legal/mca), and
[Data Processing Addendum](https://typesafe.ai/legal/data-processing) for its
current terms and international-transfer information. Those documents describe
TypeSafe's processing and can change independently of this policy.

Apple processes any app download, device backup, and (where applicable)
TestFlight activity under its own policies. Any link you choose to open is
governed by the destination site's privacy policy.

## Retention

The app uses the local retention periods stated above: current drafts and
pending shared imports expire after up to 24 hours, and saved history expires
after up to 30 days. Expired records are cleaned up when the app accesses the
relevant store; iOS does not guarantee that cleanup will run at the exact expiry
time if the app is never opened. You can remove local records sooner using the
app's controls.

We retain support correspondence only for as long as reasonably needed to
respond, manage related issues, and meet legal obligations. TypeSafe and other
providers apply their own retention periods; Digital Pulse d.o.o. cannot delete
provider records through the app.

## Your choices and rights

You can use the app without submitting a check. Do not tap **Check message** if
you do not want the current text sent to TypeSafe. You can delete a draft,
disable or clear local history, and discard shared imports from the app.

Depending on where you live and applicable law, you may have rights to request
access, correction, deletion, restriction, portability, or to object to certain
processing. Contact [hello@digitalpulsedoo.com](mailto:hello@digitalpulsedoo.com)
to make a request. To reduce exposure, include an approximate request time and
do not resend sensitive message content unless we ask for it securely. Because
the app has no account or server-side message history, we may be unable to
identify a particular provider request. You may also have the right to complain
to your local data-protection authority.

## Children

BeforeYouTrust is not directed to children. TypeSafe's published policy says
its services are not directed to people under 18. Do not submit a child's
personal information through the app. Contact us if you believe it has been
provided so we can consider appropriate next steps.

## Changes to this policy

We may update this policy as the app or its service providers change. We will
publish the updated version here and revise the effective date. The current
version is also intended to be linked from the app's Settings screen.
