# Send mail using amazon ses
[![Run On Dcoder](https://static-content.dcoder.tech/dcoder-assets/run-on-dcoder.svg)](https://code.dcoder.tech/feed/block/60c4910e0851ae7b224ac5c6)

## Description
Send an email using amazon ses with optional attachments.

## Inputs
#### **SES_KEY**  *Text*
aws ses key
#### **SES_SECRET**  *Text*
aws ses secret
#### **SES_REGION**  *Text*
aws ses region.
#### **SES_SENDER**  *Text*
sender name and email id
#### **MAIL_TO**  *Text*
Reciever's email address.
#### **MAIL_SUBJECT**  *Text*
mail subject
#### **MAIL_BODY**  *Text*
mail body.
#### **attachmentList**  *JsonArray*
A jsonarray of string, ie array of paths or urls of files to be attached.

## Output

