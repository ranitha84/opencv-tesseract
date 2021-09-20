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

**Sample of extracted text from the filled form**

name
====
Anitha Rajamani


business_name
=============
Bank Now York Mallon


exempt_payee_code
=================
121242


exempt_fatca_code
=================
I212121 2121212


address
=======
No 174 Freemont Steet  Freenont  CA 98754


city_state_zip
==============
California CA 121212


requesters_name_address
=======================
No 174 Freemont Street  Freenont CA 98754


account_numbers
===============
23897 23847 2387 47 2387 47 25347 82347 237 487 237 4823974


social_security_number
======================
3  2  4   2  3   2  3  4  8


employee_ein
============
3  4   3  9  8  5  7  3  4


