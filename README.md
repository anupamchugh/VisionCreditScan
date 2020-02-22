# VisionCreditScan

Scan credit and other buisness cards using rectangle detection, followed by a perspective correction to handle distortion.

Finally, I've allowed the user to select the region of interest through gestures and extract the relevant
information using Vision's Text Recognizer.

Doing so, not only makes it a secure way of extracting digits, but also allows us to step away from regular
expressions for parsing texts. Regular Expressions are inefficient in scenarios, since there's not gurantee of the number
of digits that'll be there on the card. For example AMEX cards don't have 16 digits.

# Demo

![alt-text](https://github.com/anupamchugh/VisionCreditScan/blob/master/vision-credit-card-scanner-output.gif)

## Article
[Scanning Credit Cards Using Computer Vision in iOS](https://heartbeat.fritz.ai/scanning-credit-cards-with-computer-vision-on-ios-c3f4d8912de4)

