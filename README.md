# opencv-tesseract

- **fw9_format.png** (Sample template with bounding boxes) and **fw9_format_1.png** (Sample form filled with details) files uploaded to this project were used for training the sample files. 
- Pytesseract and OpenCV were used for extracting text from W9 forms 
- Code first aligns the filled form
- Based on the bounding boxes defined, it would fetch the corresponding text images
- Smoothening techniques are performed on the images extracted
- OCR is applied on the image to extract the text details

**Sample of Stacked images**
![image](https://user-images.githubusercontent.com/13603542/133975747-77b53272-e648-4442-963e-e0f36b0b9958.png)

**Sample aligned image**
![image](https://user-images.githubusercontent.com/13603542/133975834-82c393b6-0d5d-47aa-ba47-9cb74e41da24.png)


**Sample image after performing smoothening on the image extracted based on the bounding boxes**
![image](https://user-images.githubusercontent.com/13603542/133975926-128c9d64-a306-40a3-a05a-d43b777a1aa3.png)

**Contour detection is used for detecting checkbox selection.**
- If total number of contours identified is greater than 3, then we consider the checkbox as selected

**Sample of extracted text from the filled form after cleaning text**

name
====
Anitha Rajamani


business_name
=============
HDFC Bank  Kodambakkam


exempt_payee_code
=================
324234


exempt_fatca_code
=================
76867867867867


address
=======
142121234  Freemont  texas  new york states applicable  Lets see


city_state_zip
==============
1343242342 Freemont  texas  new vork states applicable  Lets ses


requesters_name_address
=======================
3A2342Z3432423432423A23423423432423423 4435345345345345HSHASHSHS34SHS3S 12121234 Freemont  texas  new york st


account_numbers
===============
sdifiksdikfisdkif589G0458934589384s dfmnkis akdpls apfksdikaisdpfkdkfifu34958093489230985893485 798347 58934579843


employee_ein
============
767867867


individual_sole_proprietor
==========================
False


c_corporation
=============
False


s_corporation
=============
False


partnership
===========
False


trust_estate
============
False


limited_liability
=================
False


others
======
False


other_intstructions
===================
tes terterjfbjdkshfjds fhdjshfjsdhfjsdhfjsdhfjsdhfiksdfhiksdfhskdjfhs 


limited_liability_instruction
=============================
c


social_security_number
======================
2347678672


