# Sample Solution Request App

## Overview
The Sample Solution Request App is a streamlined solution built with PowerApps for managing sample requests and providing customized solutions to clients. Users can submit detailed sample solution requests, upload supporting documents and media, and track the status of their requests. The app also includes a secure admin login page for administrators to review requests, provide feedback, and upload solution documentation.

---

## Features
- **Sample Solution Request Form**:
  - Users can fill out a form to provide request details, including:
    - Client Information
    - Sample Requirements
    - Deadline or Delivery Date
    - Additional Notes
- **Media and Document Uploads**:
  - Users can upload supporting documents, images, and video links for more clarity.
- **Admin Panel**:
  - A secure admin login page with user credential validation for accessing admin-only features.
  - Admins can review requests, upload solution documents, and provide feedback to users.
- **Document and Media Management**:
  - Uploaded documents, images, and video links are stored in a SharePoint Document Library for centralized access via Power Automate.
- **Feedback Mechanism**:
  - Admins can give feedback on submitted requests, which users can view in the app.
- **Automated Email Notifications**:
  - Notify relevant stakeholders when a new sample request is submitted or when a solution is ready.
  - Emails include the request details, media links, and any provided feedback.
- **Data Storage**:
  - Request data is stored in an Excel file for easy tracking and reporting.
  - Supporting documents are managed in SharePoint.
- **Request Tracking**:
  - Users can track the status of their sample requests and view admin responses.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **Microsoft Power Automate**:
  - Automated email notifications and document uploads
- **Excel**:
  - Data storage for tracking requests
- **SharePoint**:
  - Backend for document and media storage
- **Office 365 Outlook Integration**:
  - Email functionality

---

## How It Works
1. **Request Submission**:
   - Users fill out the sample solution request form with all necessary details and upload supporting documents or media.
   - Data is stored in Excel, and uploaded media is saved to a SharePoint Document Library.
2. **Admin Review**:
   - Admins log in through the secure admin panel to review sample solution requests.
   - Admins can upload solution documents and provide feedback, which is displayed to users.
3. **Media and Documentation**:
   - Supporting documents, images, and video links are managed using Power Automate flows for seamless integration with SharePoint.
4. **Automated Notifications**:
   - Notifications are sent to stakeholders when new requests are submitted or when solutions are provided.
5. **Request Tracking**:
   - Users can view the status of their requests and any updates or feedback from the admin.

---

## Benefits
- Simplifies the process of submitting and managing sample requests.
- Enhances clarity with document and media uploads.
- Provides secure admin access for reviewing requests and providing solutions.
- Keeps stakeholders informed with automated notifications.
- Centralized storage of data and media for better traceability.

---

## Future Enhancements
- Integration with Power BI for advanced analytics and status dashboards.
- Adding multi-step workflows for complex request approvals.
- SMS alerts for urgent request updates.

---

