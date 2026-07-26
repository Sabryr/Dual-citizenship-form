---
layout: page
title: Example Dual Citizenship Application
permalink: /application-demo/
---

# Exmple Application for Dual Citizenship (Resumption / Retention)

* Author: Sabry Razick Ph.D
* Date: 26-07-2026
* Contact email: sabryr@gmail.com
* Link to original form : https://stockholm.embassy.gov.lk/wp-content/uploads/2026/07/Resumption.pdf
* Original form Hosted at: https://stockholm.embassy.gov.lk

This document is prepared to provide suggestions to improve the applicants  experience when submitting an application form for dual citizenship. I have my self filled the current form and also assisted many applicants during an mobile consular session. 

Consolidating redundant information requests would greatly improve the user experience, reduce applicant fatigue, and minimize the risk of contradictory information being submitted.

### Redundancies across forms

The following table highlights the most prominent duplicate information requested across the different sections of the document:

The form contains three sub forms 
1. Initial form
2. Personal Particulars Form
3. Computerised Data Sheet

| Data Field | Initial form | Personal Particulars Form | Computerized Data Sheet |
| --- | --- | --- | --- |
| Applicant Name | Requests Full Name and Name with Initials in Section 2.01.| Requests Name in Full in Question 01.| Requests Full Name in Question 1.|
| Date & Place of Birth | Requests Date and Place of Birth in Section 2.03. | Requests Date, Place, and Country of Birth in Question 02. | Requests Date and Place of Birth in Questions 4 and 5.|
| Contact Details | Requests Addresses (Sri Lankan and Foreign), Email, and Contact Number in Section 2.02. | Requests Foreign Address, Previous Sri Lankan Address, Email, and Phone Numbers in Questions 08, 12, 13, 14, and 15. | Requests Address, Email, and Phone Numbers in Questions 2, 10, and 11.|
| Profession | Requests Profession or Occupation in Section 2.08.| Requests Profession or Occupation in Question 07. | Requests Profession or Occupation in Question 3.|
| Parental Details | Requests Father's and Mother's Names, Date of Birth, and Place of Birth in Section 4.01. | Requests Father's and Mother's Names and Sri Lankan Addresses in Questions 18 and 19.| Requests Father's and Mother's Names with Initials in Questions 6 and 7. |
|Foreign Citizenship | Requests Country, Date Acquired, Certificate Number, and Passport Number in Section 3. | Requests Present/Previous Citizenship, Date Acquired, and Foreign Passport Number in Questions 04, 05, 06, and 11. | Requests particulars of other nationalities in Question 9.|

### Additional Redundant Information

Beyond the major fields above, there are several other areas where the application asks for duplicate or overlapping information:

* Spouse Details: Form Initial form asks for the spouse's name and nationality. The Personal Particulars form repeats this and additionally asks for previous citizenship, passport number, and address.


* Children Details: Form Initial form requires the name, date of birth, and nationality of children. The Personal Particulars form separately asks for their names, sex, and date of birth.

* Sri Lankan Passport/NIC: Form Initial form asks for the National Identity Card number and previous Sri Lankan passport details. The Personal Particulars form repeats the request for the NIC number, passport number, and issue dates.

* Checklist Repetition: The cover page checklist requests the applicant's Contact No, Email Address, and Residential Address, which are already heavily repeated in the core forms.


### Recommendations for Improvement

To streamline the form and reduce confusion, the issuing authority should consider merging the Personal Particulars Form and the Computerised Data Sheet directly into Initial form. By creating a single, unified "Applicant Information" section at the beginning of the document, the applicant would only need to write their name, birth details, contact information, and family history once.

** As printers are used less in European housholds and we also recomend tha this form to availble for online submission. An example is provided below.**

## Please not that this an example to suggest improvments and not an form you should use

<form id="demoForm" style="max-width: 900px; padding: 20px; border: 1px solid #ddd; border-radius: 8px; background-color: #fcfcfc;">
        
    <!-- SECTION 1: Application Type & Eligibility -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">1. Application Type & Eligibility</legend>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Application Type</label>
                <select name="applicationType" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
                    <option value="">Select...</option>
                    <option value="resumption">Resumption (Section 19(2))</option>
                    <option value="retention">Retention (Section 19(3))</option>
                </select>
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Eligible Category</label>
                <select name="eligibleCategory" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
                    <option value="">Select...</option>
                    <option value="A">A - Exceeds 55 years of age</option>
                    <option value="B">B - Academic/Professional qualifications</option>
                    <option value="C">C - Assets/Properties >= Rs. 2.5 million</option>
                    <option value="D">D - Fixed deposit >= Rs. 2.5 million</option>
                    <option value="E">E - Fixed deposit >= USD 25,000</option>
                    <option value="F">F - Treasury Bonds/SIA >= USD 25,000</option>
                    <option value="G">G - Spouse or unmarried child (<22 yrs)</option>
                </select>
            </div>
        </div>
        
        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Claim to Sri Lankan Citizenship</label>
        <select name="claimToCitizenship" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
            <option value="">Select...</option>
            <option value="descent">By Descent</option>
            <option value="registration">By Registration</option>
        </select>

        <label for="reasonsForApplying" style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Reasons for applying / Details relating to benefits accrued to Sri Lanka:</label>
        <textarea id="reasonsForApplying" name="reasonsForApplying" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 80px; resize: vertical;"></textarea>
    </fieldset>

    <!-- SECTION 2: Personal Information -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">2. Personal Information</legend>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="fullName" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Full Name</label>
                <input type="text" id="fullName" name="fullName" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="nameWithInitials" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Name with Initials</label>
                <input type="text" id="nameWithInitials" name="nameWithInitials" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
            </div>
        </div>

        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="dob" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Date of Birth</label>
                <input type="date" id="dob" name="dob" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="birthPlace" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Place & Country of Birth</label>
                <input type="text" id="birthPlace" name="birthPlace" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="gender" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Gender</label>
                <select id="gender" name="gender" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
                    <option value="">Select...</option>
                    <option value="Male">Male</option>
                    <option value="Female">Female</option>
                </select>
            </div>
        </div>

        <div style="display: flex; gap: 15px; flex-wrap: wrap;">
            <div style="flex: 1; min-width: 200px;">
                <label for="birthCertNo" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Birth Certificate No. & District</label>
                <input type="text" id="birthCertNo" name="birthCertNo" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="profession" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Profession or Occupation</label>
                <input type="text" id="profession" name="profession" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>
    </fieldset>

    <!-- SECTION 3: Contact & Address Details -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">3. Contact & Address Details</legend>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="email" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Email Address</label>
                <input type="email" id="email" name="email" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>
            </div>
        </div>

        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="foreignPhoneRes" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Foreign Telephone (Residence)</label>
                <input type="text" id="foreignPhoneRes" name="foreignPhoneRes" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="foreignPhoneMob" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Foreign Telephone (Mobile)</label>
                <input type="text" id="foreignPhoneMob" name="foreignPhoneMob" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>

        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="localPhoneRes" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Sri Lanka Telephone (Residence)</label>
                <input type="text" id="localPhoneRes" name="localPhoneRes" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="localPhoneMob" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Sri Lanka Telephone (Mobile)</label>
                <input type="text" id="localPhoneMob" name="localPhoneMob" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>

        <label for="foreignAddress" style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Current Residential Address (Foreign)</label>
        <input type="text" id="foreignAddress" name="foreignAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;" required>

        <label for="localAddress" style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Address in Sri Lanka (Current)</label>
        <input type="text" id="localAddress" name="localAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">

        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Previous Residential Address in Sri Lanka (With Period & Police Area)</label>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><input type="text" name="prevAddressSL" placeholder="Address" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><input type="text" name="prevAddressPeriod" placeholder="Period (From - To)" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><input type="text" name="prevAddressPolice" placeholder="Police Area" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>

        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Details of a Local Contact Person in Sri Lanka</label>
        <div style="display: flex; gap: 15px; flex-wrap: wrap;">
            <div style="flex: 1; min-width: 200px;"><input type="text" name="contactPersonName" placeholder="Name" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><input type="text" name="contactPersonPhone" placeholder="Contact Number" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
    </fieldset>

    <!-- SECTION 4: Citizenship & Passport Details -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">4. Citizenship & Passport Details</legend>
        
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="slNIC" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Sri Lankan NIC No. & Date of Issue</label>
                <input type="text" id="slNIC" name="slNIC" placeholder="NIC No. / YYYY-MM-DD" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="slPassport" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Sri Lanka Passport No. / Date / Place of Issue</label>
                <input type="text" id="slPassport" name="slPassport" placeholder="Passport No. / Date / Place" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>

        <hr style="border: 0; border-top: 1px solid #ddd; margin: 20px 0;">

        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="citizenshipAtBirth" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Citizenship at Birth</label>
                <input type="text" id="citizenshipAtBirth" name="citizenshipAtBirth" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="previousCitizenship" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Previous Citizenship(s) (if any)</label>
                <input type="text" id="previousCitizenship" name="previousCitizenship" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>

        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;">
                <label for="currentForeignCitizenship" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Country of Present Foreign Citizenship</label>
                <input type="text" id="currentForeignCitizenship" name="currentForeignCitizenship" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="dateAcquiredForeign" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Date of Acquiring Present Citizenship</label>
                <input type="date" id="dateAcquiredForeign" name="dateAcquiredForeign" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="foreignCertNo" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Foreign Citizenship Cert No.</label>
                <input type="text" id="foreignCertNo" name="foreignCertNo" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>

        <div style="display: flex; gap: 15px; flex-wrap: wrap;">
            <div style="flex: 1; min-width: 200px;">
                <label for="foreignPassport" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Foreign Passport No. / Country & Date of Issue</label>
                <input type="text" id="foreignPassport" name="foreignPassport" placeholder="Passport No. / Country / Date" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
            <div style="flex: 1; min-width: 200px;">
                <label for="permanentResidence" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Permanent Residence Status (If applying for Retention)</label>
                <input type="text" id="permanentResidence" name="permanentResidence" placeholder="Country / Date Granted" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
            </div>
        </div>
    </fieldset>

    <!-- SECTION 5: Family Details -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">5. Family Details</legend>
        
        <h4 style="margin-top: 0;">Spouse's Details</h4>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Name</label><input type="text" name="spouseName" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Present Nationality</label><input type="text" name="spouseNationality" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Previous Citizenship</label><input type="text" name="spousePrevCitizenship" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Passport No / NIC</label><input type="text" name="spousePassportNIC" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Address in Sri Lanka</label><input type="text" name="spouseSLAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Mobile No</label><input type="text" name="spouseMobile" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>

        <hr style="border: 0; border-top: 1px solid #ddd; margin: 20px 0;">
        
        <h4>Applicant's Parents</h4>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Father's Name (with initials)</label><input type="text" name="appFatherName" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Date & Place of Birth</label><input type="text" name="appFatherBirth" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Address in SL & Police Area</label><input type="text" name="appFatherAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">SL Citizenship Reg Cert Details (if app)</label><input type="text" name="appFatherReg" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Mother's Name (with initials)</label><input type="text" name="appMotherName" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Date & Place of Birth</label><input type="text" name="appMotherBirth" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Address in SL & Police Area</label><input type="text" name="appMotherAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">SL Citizenship Reg Cert Details (if app)</label><input type="text" name="appMotherReg" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>

        <hr style="border: 0; border-top: 1px solid #ddd; margin: 20px 0;">

        <h4>Spouse's Parents</h4>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Father's Name</label><input type="text" name="spouseFatherName" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Address in SL & Police Area</label><input type="text" name="spouseFatherAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin-bottom: 10px;">
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Mother's Name</label><input type="text" name="spouseMotherName" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
            <div style="flex: 1; min-width: 200px;"><label style="display: block; font-weight: bold; font-size: 0.9em;">Address in SL & Police Area</label><input type="text" name="spouseMotherAddress" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></div>
        </div>

        <hr style="border: 0; border-top: 1px solid #ddd; margin: 20px 0;">

        <h4>Details of Children Applying for Dual Citizenship</h4>
        <table style="width:100%; text-align:left; border-collapse: collapse;">
            <tr>
                <th style="border-bottom: 1px solid #ccc; padding-bottom: 8px;">Name of the Child</th>
                <th style="border-bottom: 1px solid #ccc; padding-bottom: 8px;">Date of Birth</th>
                <th style="border-bottom: 1px solid #ccc; padding-bottom: 8px;">Sex</th>
                <th style="border-bottom: 1px solid #ccc; padding-bottom: 8px;">Nationality</th>
            </tr>
            <tr>
                <td style="padding-top: 8px;"><input type="text" name="child1Name" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;"></td>
                <td style="padding-top: 8px;"><input type="date" name="child1DOB" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;"></td>
                <td style="padding-top: 8px;">
                    <select name="child1Sex" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;">
                        <option value="">...</option><option value="M">M</option><option value="F">F</option>
                    </select>
                </td>
                <td style="padding-top: 8px;"><input type="text" name="child1Nat" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;"></td>
            </tr>
            <tr>
                <td style="padding-top: 8px;"><input type="text" name="child2Name" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;"></td>
                <td style="padding-top: 8px;"><input type="date" name="child2DOB" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;"></td>
                <td style="padding-top: 8px;">
                    <select name="child2Sex" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;">
                        <option value="">...</option><option value="M">M</option><option value="F">F</option>
                    </select>
                </td>
                <td style="padding-top: 8px;"><input type="text" name="child2Nat" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;"></td>
            </tr>
        </table>
    </fieldset>

    <!-- SECTION 6: Background Information -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">6. Background Information</legend>
        <label for="orgMembership" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Were you a member of a cultural, social, religious, or political organization in Sri Lanka? If so, give details:</label>
        <textarea id="orgMembership" name="orgMembership" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 80px; resize: vertical; margin-bottom: 12px;"></textarea>

        <label for="convictions" style="display: block; font-weight: bold; font-size: 0.9em; margin-bottom: 4px;">Have you been convicted or punished in a court of law, in any country? If so, give details:</label>
        <textarea id="convictions" name="convictions" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 80px; resize: vertical;"></textarea>
    </fieldset>

    <!-- SECTION 7: Category Specific Eligibility Details -->
    <fieldset style="border: 1px solid #aaa; border-radius: 5px; margin-bottom: 25px; padding: 20px; background-color: #f9f9f9;">
        <legend style="font-weight: bold; padding: 5px 10px; color: #004494; background-color: #fff; border: 1px solid #aaa; border-radius: 3px;">7. Category Specific Eligibility Details</legend>
        <p style="font-size: 0.9em; color: #555;"><i>Fill out the section that applies to your selected Eligible Category (B, C, D, E, or F).</i></p>
        
        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Category B: Academic / Professional Qualifications (Degree/Diploma/Qualification, Institution, Period)</label>
        <textarea name="academicProfQual" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 60px; resize: vertical;"></textarea>

        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Category C: Assets / Immovable Properties in Sri Lanka (Details, Deed/Ref No, Estimated Value LKR)</label>
        <textarea name="assetsProperties" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 60px; resize: vertical;"></textarea>

        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Category D & E: Fixed Deposits (Name of Bank, Account No, Deposit Amount LKR/USD, Date of Maturity)</label>
        <textarea name="fixedDeposits" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 60px; resize: vertical;"></textarea>

        <label style="display: block; font-weight: bold; font-size: 0.9em; margin-top: 12px; margin-bottom: 4px;">Category F: Treasury Bonds & Security Investment Accounts (Invested Value USD, Date of Maturity)</label>
        <textarea name="treasuryBonds" style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px; height: 60px; resize: vertical;"></textarea>
    </fieldset>

    <button type="submit" style="background-color: #004494; color: white; padding: 12px 25px; border: none; border-radius: 4px; font-size: 1.1em; cursor: pointer; display: block; width: 100%; margin-top: 20px;">Submit (Demo)</button>
</form>

<script>
  document.getElementById('demoForm').addEventListener('submit', function(event) {
    // Prevents the page from reloading and appending variables to the URL
    event.preventDefault();
    alert('This is a demonstration form. No data has been submitted or stored.');
  });
</script>
