## Context

This issue was discovered during exploratory testing of the Indeed website.

The issue occurs only when the Google Translate browser extension automatically translates the Dutch version of Indeed into English.
<br><br><br>



**Title:** <br>
Skill editing fails when Google Translate extension is enabled

<br>

**Environment:** <br>
indeed.com website
Operating System: Windows 11
Browser: Google Chrome, version: 150.0.7871.102 (Official version) (64-bit)
Date: 15.07.2026
Google Translate Extension: Enabled
Translation: Dutch → English

<br>

**Severity:**<br>
low

<br>

**Priority:** <br>
low

<br>

**Preconditions:** <br>
User has a valid Indeed account.
User is logged in.
Google Translate extension is enabled.
Automatic translation from Dutch to English is active.

<br>

**Steps to Reproduce:** <br>
1. Log in to Indeed.
2. Open Profile.
3. Navigate to Qualifications → Skills.
4. Click Edit next to an existing skill.
5. Modify the skill by typing any text.

<br>

**Expected result:** <br>
The user should be able to edit an existing skill and save the changes successfully.

<br>

**Actual result:** <br>
While typing, the edit dialog unexpectedly closes and the user is redirected to a generic error page displaying:

"We currently have a problem..."

As a result, the user cannot complete editing or save the changes.

<br>

**Reproducibility:** <br>
3/3 attempts

<br>

**Attachments:** <br>
screenshot

<br>

**Notes:** <br>
The issue appears only when the Google Translate browser extension automatically translates the Dutch version of Indeed into English. The issue could not be reproduced after disabling automatic translation.

<br>

**Context:** <br>
Exploratory testing of the Indeed website.

<br>

**Category:** <br>
UI / Functional


<img width="1736" height="1028" alt="Full Screen" src="https://github.com/user-attachments/assets/f148a168-7bb1-4f36-9183-a222b1f94c41" />
