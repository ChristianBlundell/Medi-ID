# Medi-ID
Medi ID is a bracelet that contains NFC technology which directs the user to a progressive website containing the medical information of a patient. The progressive website is developed using PHP scripts. The user taps the bracelet on their phone to access the website, logging in with predetermined credentials. This repository contains the contents of the project, including documentation and source code of the project. The project must use the physical Medi ID bracelet to properly demo the project, but the link that the bracelet redirects the user can be found here: https://mediid.000webhostapp.com/login_form.php

*Blog Post*
MEDI ID
Team Name
Medi ID Group
Timeline
Fall 2022 – Spring 2023
Students
Christian Blundell
Ivan Chu
Ahamad Natsheh
Mahmoud Natsheh
Alex Stringer
Sponsor
Shawn Gieser
Abstract
Medi ID is a bracelet with an NFC tag built into the bracelet that stores the user’s
medical information. This is useful for first responders that give aid to a person who is
physically unable to document their medical information. A verified EMT or first
responder can scan the bracelet and use the Medi ID progressive web application to
view that person’s medical background and insurance information. Access to this
information can be crucial and potentially life-saving for a person who is in an
emergency situation.
Background
Current models of the Medical ID bracelet use a QR code to scan and open a webpage
with the user’s information on it. The problem with the QR code method of retrieving the
user-stored data is that the QR code on current models is facing the user’s wrist and the
user’s sweat over time fades the QR code out, causing the user to re-order the bracelet,
costing the user more in the long term. Furthermore, the bracelet does not have enough
security. NFC does not fade out and can be read using a phone just like a QR code, this
would not change the technology needed to read the information and would enhance
the technology currently used. Furthermore, we will add a layer of verification where the
user has to log in before exposing the user’s information to ensure that only the allowed
users are accessing the medical information, which mitigates the problem of insufficient
security.
Project Requirements
● A durable, long-lasting bracelet must be developed to hold an NFC chip
● A verified user can scan the bracelet
● Users can register an account to the progressive web application
● Users can log in to their account in the progressive web application
● Users can add/edit/delete their own medical information
● The progressive web application must be accessible to patients and verified
users at all times
● A manual must be created to demonstrate how the bracelet works and how to set
up a patient profile on the progressive web application
● NFC chip must be stored inside the bracelet, with a unique key that belongs only
to one user
● A database must be created to support the data of all users that access the
progressive web application
● Password encryption must be implemented to protect user accounts and
maintain security
System Overview
The medical identification diagram has three main layers the first layer is the tap
function, once a phone taps the NFC chip in the medical identification bracelet it will
redirect the user to our website and ask them for their credentials. This directs the user
to the next layer which interacts with the cloud or database, this is where all the user’s
information will be stored. This takes us to the final layer which is the user interface
layer, this is where all the user’s data will be displayed to either the user or the medical
professional.
Architectural Layer Diagram
Results
Our finished product of the Medi ID Bracelet matched the general requirements specified by the
sponsor and intended users. The hardware matches the requirements declared by our group, and
the software development matched the overall system layout that we designed in our ADS and
DDS layouts.
During this project, we learned the beneficial process of designing products using Agile
methodology, which includes working through sprints and documenting the design process. This
improves customer interaction, flexibility, productivity, constant development rates, and overall
risk reduction.
Demo Video
Medi ID Bracelet Prototype
Future Work
Future Requirements include Introducing Optical Character Recognition to the patient info portal to add
images of medical documents. Another requirement would be designing the user manual for the bracelet
and setting up an automatic registration system for new users. Product packaging and secure sign-on
methods (Face ID, Touch ID) have also been considered as future requirements.
Project Files
Project Charter
System Requirements Specification
Architectural Design Specification
Detailed Design Specification
Poster
References
1. Bai RMF Resource Center. https://rmf.org/wp-content/uploads/2017/10/CNSSI-4009.pdf.
2. “IEC/IEEE 82079-1:2019.” ISO, 20 May 2019, https://www.iso.org/standard/71620.html.
3. “ISO 18530:2021.” ISO, 27 Jan. 2021, https://www.iso.org/standard/77333.html.
4. “ISO 20302:2022.” ISO, 17 Jan. 2022, https://www.iso.org/standard/79931.html.
5. Jethanandani, Mahesh, et al. “RFC 9314.” RFC 9314: YANG Data Model for Bidirectional
Forwarding Detection (BFD), https://www.rfc-editor.org/rfc/rfc9314.html.
6. “NIST Special Publication 800-63B.” Pages.nist.gov,
https://pages.nist.gov/800-63-3/sp800-63b.html.
