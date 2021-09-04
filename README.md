# AWS Email Lambda
I git repo that with a little setup you can call to send emails, passing a target email, subject, message.


You will need to navigate to your gmail to get a key that you can save as an OS envioronment variable in AWS.

Explanation here:
https://support.google.com/googleapi/answer/6158862?hl=en

Also some additional details if you would like to properly format your email:
https://docs.python.org/3/library/email.mime.html

Also you can text using this if you format the email address based on the carrier of the target phone/email address. List of how to format the target email to get it to text to a phone number:
https://github.com/cubiclesoft/email_sms_mms_gateways/blob/master/sms_mms_gateways.txt
Simply insert the phone number properly into the email string.

