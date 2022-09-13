# CWRU-cybersec-21-Forensics
Documentation of the Digital Forensics Investigation project from the CWRU Cybersecurity course.

## Week 21 Homework: Digital Forensics

In this week's assignment, you will continue to work with your group to continue the final report you began in class. The instructions are included here again for reference. There is also a bonus activity aimed to sharpen your skills in locating and identifying data in a forensic image.

### Scenario

Just as in a real-world scenario, you will complete a final report to present your findings. You will work with your team to fill out the report.

 - The final report should be submitted as the homework deliverable for this week. Everything your group has completed in class should be included. What you do not finish today can be continued at home.

 - Use the [Final Case Report](https://docs.google.com/document/d/1H528_nPqhfp_eOCzvyviwx5U3M1NiPTGtIFaoQoANbY/edit#heading=h.w4pkinqwxqi8) Google Doc template to complete your report. Make a copy and be sure that each student has editing access. This will allow everyone in the group to access and work on the document at the same time.

  - Each group will turn in one completed report to be graded.

  - Use the following resource to help guide your work:

     - [iPhone Forensics - Important Files and Databases](https://docs.google.com/document/d/10CWGqTvu09mrSn7Tg7xoKNWBrjeW1wCmXoqB58xYr0k/edit#)

### Lab Environnement

- This homework will use the Digital Forensics - Autopsy lab in Kali Linux.

- You will find the `tracy-phone-2012-07-15.final.E01` file located in the `/corpus` directory in Autopsy.

### Instructions

You've examined and documented quite a bit of information from the iPhone image file. Now you will use that documentation to build a final report.

1. First, fill out the following evidence worksheet to document the case's WiFi and GPS locations. You will add this, along with the Correspondence Worksheet, to the final report.

    - [Location Information Worksheet](https://docs.google.com/document/d/19ckQwWc2iPh7qzKVDnBAKoBS-DpVBCb2cFfAbLNrULk/edit#heading=h.x6git33zpmpj)

    Your group can look for WiFi and GPS info the following directories:

     - Find information about WiFi locations in `root/Library/Caches/locationd/consolidated.db`.

       - **Note:** Input GPS coordinates into Google Maps to see the locations.

     - Find information related to WiFi and cell tower location information in `consolidated.db`.

2. Working in your group's copy of the report template, add content and details as indicated in each section.

   - You will rely on the Locations Information and Correspondence Evidence Worksheets you've completed so far. Additionally, you can use the **iPhone Forensics - Important Files and Databases** resource to analyze and find more information to support your case, such as Voicemails and notes from the Notepad iPhone application.

   - Be sure to add to the report the equipment and tools you used to gather and analyze the evidence.

      - For example, Autopsy, the operating system (Kali Linux), text editors (Nano), etc.

   - When including pictures from the iPhone, please use the time stamp of the **Created time** from autopsy. 

 ### Submission Guidelines

 - Each individual should submit their own completed Final Case Report document.

---

## Week 21 Homework Solution: Digital Forensics

Refer to the following solution files for the homework worksheets: 

* [Week 21 Homework Solution: Digital Forensics - Final Report](https://github.com/thunder-katz/CWRU-cybersec-21-Forensics/blob/main/21.3%20The%20Final%20Report_.pdf)  

---
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
