[![Apache 2 license](https://img.shields.io/badge/license-Apache2-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0)

Amazon SNS Notification Verification with Python, M2Crypto. When the SNS pushes a notification, a receiver should verify the origin/integrity of the push notification (AWS) using the signature and certificate provided in the notification data. The function `verify_sns_notification` takes the request object and verifies the origin/integrity of the message.
