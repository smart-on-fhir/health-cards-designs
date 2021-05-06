# SMART Health Cards Designs
This work provides SMART Health Cards (https://smarthealth.cards/) and the  implementers with (1) guidance on appropriate display and use of SMART Health Cards and (2) reference designs.

The overall objective is to encourage consistent visual representations of SMART Health Cards to increase recognition among users and verifiers.

Note that these reference designs refer to the VCI SMART Health Cards: Vaccination & Testing Implementation Guide (https://vci.org/ig/vaccination-and-testing/)


## Designs
PDF/ Printable Document

Patient portal page

Mobile apps (forthcoming)

Designs are available as PDF and SVG in this repo, as well as original Figma here: https://www.figma.com/community/file/969941235839543745/SMART%C2%AE-Health-Card-Reference-Designs


## Elements

### Patient and Clinical Data
All patient data and clinical data that are present in the SMART Health Card should be displayed clearly, prominently, and clear labels, as they are in the corresponding data payload.

If data must be reformatted, adjusted for legibility, or translated, make every effort to ensure that they are consistent with the original data payload.

### QR Code
QR codes should be presented in close proximity to the patient and clinical data as described above.

If multiple SMART Health Cards are presented, data should be displayed in close proximity to the corresponding QR code to avoid confusion over what is being shared.

QR Codes should be rendered in black on a white background only to maximize contrast.

The text “SMART Health Cards” and SMART logo should appear next to the QR code. (Note: logo use agreement is work-in-progress.)

### Buttons and Interactive Elements
Buttons and interactive elements enable functions including  

* Downloading one or more SMART Health Cards QR as part of a PDF document
* Downloading one or more SMART Health Cards as a .smart-health-card file
* Displaying a SMART Health Card as a QR code

Interactive elements should be displayed in close proximity to the patient and clinical data as described above.

### Additional Information
Provide key information about SMART Health Cards, including that they 

* Hold important health information
* Can be scanned or shared to verify the information with the issuer

Provide a privacy reminder that scanning the QR code or sharing the file will transmit all of the included personal and clinical data.

Note that these records can be used with apps, services, and locations where SMART Health Cards are accepted.

Provide plain language explanations for data that might be difficult to understand, such as the Identity Assurance Level.

Where possible, provide this information in the document or the same view as the SMART Health Card. For mobile applications and other cases where space is constrained, provide a means to link out to or pop up more information.

Feel free to draw on language from the Health Cards Patient Onboarding FAQ when providing background to users (https://github.com/smart-on-fhir/health-cards/blob/main/FAQ/patient-onboarding.md)


## Use of logos
Issuers are encouraged to include their logo on SMART Health Cards as shown in the reference designs.

At this time, the use of issuer logos by third parties requires prior arrangement with and approval from issuers.

The use of the SMART logo requires adherence to the SMART brand guidelines, which can be attested to at the SMART Health IT brand page. (Note: logo use agreement is work-in-progress.)


## Participants
One group building on and contributing to the SMART Health Cards Framework is the *Vaccination Credential Initiative*. See https://vaccinationcredential.org/ for participants.
