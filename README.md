# BZGMailgunEmailValidation

A simple objective-C wrapper for the Mailgun email validation API.

http://blog.mailgun.com/post/free-email-validation-api-for-web-forms/

http://documentation.mailgun.com/api-email-validation.html

```objective-c
[BZGMailgunEmailValidation validateEmailAddress:address
                                      publicKey:YOUR_MAILGUN_PUBLIC_KEY
                                        success:^(BOOL isValid, NSString *didYouMean) {
                                            // :)
                                        } failure:^(NSError *error) {
                                            // :(
                                        }];
```
