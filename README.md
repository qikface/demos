# QikFace Demos

Currently there are two HTML pages available to demonstrate how the QikFace Facial Recogntion service can
be consumed in a web application.

## Enrolment Demonstration

The **enroldemo.html** sample demonstrates how to enrol a user by taking a photo of their face. The photo 
gets uploaded to the QikFace service where it is used to generate a Facial Identification Record that can
then be used for Facial Recogntion Verifications.

## Verification Demonstration
The **verifydemo.html** sample demonstrates how to verify a previously enrolled used. This page establishes
a WebRTC video stream to the QikFace Facial Recogntion server. The server then runs a verification against the
Facial Identification Record associated with the email address against the face in the video stream. If a high
enough verification result is generated the confidence level is returned.