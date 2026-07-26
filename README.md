---
layout: page
title: Dual Citizenship Application
permalink: /application-demo/
---

# Dual Citizenship Application (Resumption)

This form is an interactive demonstration for consolidating applicant data. It is rendered directly through GitHub Pages using standard HTML embedded within Markdown.

### Applicant Details

Please fill out the required personal and contact information below. 

<form id="demoForm" style="max-width: 800px; padding: 20px; border: 1px solid #ddd; border-radius: 8px; background-color: #fcfcfc;">
  
  <fieldset style="margin-bottom: 20px; padding: 15px; border: 1px solid #ccc; border-radius: 4px;">
    <legend style="font-weight: bold; color: #0056b3;">1. Personal Information</legend>
    
    <label for="fullName" style="display: block; margin-top: 10px; font-weight: 600;">Full Name</label>
    <input type="text" id="fullName" name="fullName" style="width: 100%; padding: 8px; margin-top: 4px; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px;" required>

    <div style="display: flex; gap: 15px; margin-top: 10px;">
      <div style="flex: 1;">
        <label for="dob" style="display: block; font-weight: 600;">Date of Birth</label>
        <input type="date" id="dob" name="dob" style="width: 100%; padding: 8px; margin-top: 4px; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px;" required>
      </div>
      <div style="flex: 1;">
        <label for="birthPlace" style="display: block; font-weight: 600;">Place of Birth</label>
        <input type="text" id="birthPlace" name="birthPlace" style="width: 100%; padding: 8px; margin-top: 4px; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px;" required>
      </div>
    </div>
  </fieldset>

  <fieldset style="margin-bottom: 20px; padding: 15px; border: 1px solid #ccc; border-radius: 4px;">
    <legend style="font-weight: bold; color: #0056b3;">2. Contact Details</legend>
    
    <div style="display: flex; gap: 15px;">
      <div style="flex: 1;">
        <label for="email" style="display: block; font-weight: 600;">Email Address</label>
        <input type="email" id="email" name="email" style="width: 100%; padding: 8px; margin-top: 4px; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px;" required>
      </div>
      <div style="flex: 1;">
        <label for="phone" style="display: block; font-weight: 600;">Phone Number</label>
        <input type="text" id="phone" name="phone" style="width: 100%; padding: 8px; margin-top: 4px; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px;" required>
      </div>
    </div>
  </fieldset>

  <button type="submit" style="background-color: #0056b3; color: white; padding: 10px 20px; border: none; border-radius: 4px; cursor: pointer; font-size: 16px;">Submit Application (Demo)</button>
</form>

<script>
  document.getElementById('demoForm').addEventListener('submit', function(event) {
    // Prevents the page from reloading and appending variables to the URL
    event.preventDefault();
    alert('This is a demonstration form. No data has been submitted or stored.');
  });
</script>
