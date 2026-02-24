# Health Connect Mobile — QA Test Checklist

**Document for:** QA Team  
**Purpose:** Verify every screen and feature by opening the app and following this list.  
**How to use:** For each item, follow the **Steps** to navigate in the app, then check whether the **Expected Result** matches. Tick **Pass** or **Fail** accordingly.

---

## How to Test

1. Install the app and log in with the user type you want to test.
2. Follow the **Steps** for each test case in order.
3. Check whether the screen/behaviour matches the **Expected Result**.
4. Tick **Pass** if it matches, **Fail** if not, and add a note in **Notes** when needed.

---

# Part A — Bottom Tabs

---

## A1. Home Tab

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| A1.1 | Home dashboard | Open the app. The **Home** tab should be selected at the bottom. | Home screen loads; menu/cards/service list visible. Header green (#3BB54A). | ☐ | ☐ | |
| A1.2 | My Appointment | Home → tap the option that opens "My Appointment". | Appointment list/UI opens. | ☐ | ☐ | |
| A1.3 | Online Lab Report | Home → tap Lab Report / Online Report link or button. | Online lab report screen opens. | ☐ | ☐ | |
| A1.4 | Notification list | Home → tap Notification icon/menu. | Notification list page opens. | ☐ | ☐ | |
| A1.5 | Single notification | Home → Notifications → tap any notification. | Single notification detail opens. | ☐ | ☐ | |
| A1.6 | Family Health Card | Home → Family Health Card / family card option. | Family Health Card screen opens. | ☐ | ☐ | |
| A1.7 | Helpline | Home → Helpline / Contact option. | Helpline number/UI opens. | ☐ | ☐ | |
| A1.8 | Health Card | Home → Health Card / eHealth Card. | Health Card screen opens. | ☐ | ☐ | |
| A1.9 | Ambulance Booking | Home → Ambulance Booking. | Ambulance booking form/screen opens. | ☐ | ☐ | |
| A1.10 | Upcoming feature | Home → tap card/link for "Upcoming" or similar. | Upcoming feature message/page opens. | ☐ | ☐ | |
| A1.11 | Specialized Department (Appointment) | Home → Appointment / Department selection. | Department list or appointment flow opens. | ☐ | ☐ | |
| A1.12 | My Service | Home → "My Service". | User's booked services list opens. | ☐ | ☐ | |
| A1.13 | My Profile (from Home) | Home → Profile / Account link (if present). | Profile/Account screen opens. | ☐ | ☐ | |
| A1.14 | My Family | Home → My Family. | Family member list opens. | ☐ | ☐ | |
| A1.15 | Add Family Member | Home → My Family → Add Member. | Add Family Member form opens. | ☐ | ☐ | |
| A1.16 | Pharmacy | Home → Pharmacy. | Pharmacy screen/catalog opens. | ☐ | ☐ | |
| A1.17 | Edit Family | Home → My Family → select a member → Edit. | Edit family member screen opens. | ☐ | ☐ | |
| A1.18 | Doctor List | Home → Doctor Appointment / Find Doctor → Doctor list. | Doctor list screen opens. | ☐ | ☐ | |
| A1.19 | Doctor Profile (Personal Info) | Home → Doctor list → tap a doctor. | Doctor profile (name, specialty, slots, etc.) opens. | ☐ | ☐ | |
| A1.20 | My Doctor | Home → My Doctor. | Saved/booked doctor list opens. | ☐ | ☐ | |
| A1.21 | Doctor Slot Booking | Home → select doctor → Book slot / select date. | Slot selection screen opens. | ☐ | ☐ | |
| A1.22 | Online Link (Report) | Home → Report / Online Link (2nd version). | Online report link page opens. | ☐ | ☐ | |
| A1.23 | My Doctor Slot | Home → My Doctor → Slot / Schedule. | My doctor slot screen opens. | ☐ | ☐ | |
| A1.24 | Favorite Doctor List | Home → Add to Favorites / Favorite doctors. | Favorite doctor list opens. | ☐ | ☐ | |
| A1.25 | Appointment Confirmation | Home → complete doctor booking flow → Confirm. | Confirmation screen (success/detail) opens. | ☐ | ☐ | |
| A1.26 | My Orders | Home → My Orders. | Order list opens. | ☐ | ☐ | |
| A1.27 | General Hospital Branch | Home → General Hospital / Branch. | Branch list or map opens. | ☐ | ☐ | |
| A1.28 | My Doctor Branch | Home → My Doctor → Branch. | Doctor branch info opens. | ☐ | ☐ | |
| A1.29 | My Attendance | Home → My Attendance (if in menu). | Attendance screen opens. | ☐ | ☐ | |
| A1.30 | My Report | Home → My Report. | Report list opens. | ☐ | ☐ | |
| A1.31 | Full Body Checkup | Home → Full Body Checkup / Health Package. | Full body checkup screen opens. | ☐ | ☐ | |
| A1.32 | Home Call Service | Home → Home Call Service. | Home call service booking/UI opens. | ☐ | ☐ | |
| A1.33 | General Service | Home → General Service. | General service screen opens. | ☐ | ☐ | |
| A1.34 | Physiotherapy Service | Home → Physiotherapy. | Physiotherapy service screen opens. | ☐ | ☐ | |
| A1.35 | Single Order Detail | Home → My Orders → tap an order. | Order detail page opens. | ☐ | ☐ | |
| A1.36 | Report Detail | Home → My Report / report list → tap a report. | Report detail opens. | ☐ | ☐ | |
| A1.37 | PDF Viewer | From any report detail → PDF view / download. | Report opens in PDF viewer. | ☐ | ☐ | |
| A1.38 | Multi PDF Viewer | Where multiple PDFs are shown → tap. | Multiple PDF view/list opens. | ☐ | ☐ | |
| A1.39 | Report Tracking | Home/Report → Report Tracking. | Report status/tracking opens. | ☐ | ☐ | |
| A1.40 | Prescription | Home → Prescription (if in menu). | Prescription list/detail opens. | ☐ | ☐ | |
| A1.41 | Online Service | Home → Online Service. | Online service menu/list opens. | ☐ | ☐ | |
| A1.42 | Lab Test Screen | Home → Lab Test / Book Test. | Lab test list/category opens. | ☐ | ☐ | |
| A1.43 | Health Package Screen | Home → Health Package. | Health package list opens. | ☐ | ☐ | |
| A1.44 | BMI Calculator | Home → BMI Calculator. | BMI calculator form/result opens. | ☐ | ☐ | |
| A1.45 | Cart | Home → Cart icon / Cart. | Cart screen (item list) opens. | ☐ | ☐ | |
| A1.46 | Take Information | Home → Lab / Test book flow → Take Information step. | User input form opens. | ☐ | ☐ | |
| A1.47 | Health Screen Package | Home → Health Screen Package. | Health screen package screen opens. | ☐ | ☐ | |
| A1.48 | Lab Test (from Home) | Home → Lab Test menu. | Lab test section opens. | ☐ | ☐ | |
| A1.49 | Vital Organs | Home → Vital Organs. | Vital organs test/UI opens. | ☐ | ☐ | |
| A1.50 | Live Chat | Home → Live Chat. | Live chat screen opens. | ☐ | ☐ | |
| A1.51 | ChatGPT | Home → ChatGPT / AI Chat. | Chat interface opens. | ☐ | ☐ | |
| A1.52 | NEC Travels | Home → NEC Travels (if present). | NEC Travels screen opens. | ☐ | ☐ | |
| A1.53 | Health Package Cart | Home → select Health Package → Cart. | Health package cart opens. | ☐ | ☐ | |
| A1.54 | Web View | Any link that opens in-app web view. | Web page opens in-app. | ☐ | ☐ | |
| A1.55 | Service Department | Home → Service Department. | Service-wise department list opens. | ☐ | ☐ | |
| A1.56 | Forget Password | Login screen → Forget Password (if linked from home). | Reset password flow opens. | ☐ | ☐ | |

---

## A2. Doctor Tab

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| A2.1 | Doctor tab home | Tap **Doctor** tab at the bottom. | Doctor tab main screen (menu/options) opens. | ☐ | ☐ | |
| A2.2 | Doctor Profile | Doctor tab → select a doctor. | Doctor profile (Personal Info) opens. | ☐ | ☐ | |
| A2.3 | Doctor Slot | Doctor tab → Book doctor → select slot. | Slot selection screen opens. | ☐ | ☐ | |
| A2.4 | My Family (Doctor tab) | Doctor tab → My Family. | Family member list opens. | ☐ | ☐ | |
| A2.5 | Family Health Card | Doctor tab → Family Health Card. | Family Health Card screen opens. | ☐ | ☐ | |
| A2.6 | Edit Family / Add Member | Doctor tab → My Family → Edit or Add. | Edit or Add Member screen opens. | ☐ | ☐ | |
| A2.7 | Appointment Confirmation | Doctor tab → complete booking → Confirm. | Confirmation screen opens. | ☐ | ☐ | |
| A2.8 | My Doctor Slot / Branch | Doctor tab → My Doctor Slot or Branch. | Slot/branch info opens. | ☐ | ☐ | |
| A2.9 | Specialized Department | Doctor tab → Department. | Department list opens. | ☐ | ☐ | |
| A2.10 | Hospital Branch | Doctor tab → General Hospital Branch. | Branch list opens. | ☐ | ☐ | |
| A2.11 | Doctor List | Doctor tab → Find Doctor / List. | Doctor list opens. | ☐ | ☐ | |
| A2.12 | My Doctor | Doctor tab → My Doctor. | Booked doctor list opens. | ☐ | ☐ | |
| A2.13 | Favorite Doctor List | Doctor tab → Favorite doctors. | Favorite doctor list opens. | ☐ | ☐ | |

---

## A3. Lab Test Tab

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| A3.1 | Lab Test home | Tap **Lab Test** tab at the bottom. | Lab Test home (test/package options) opens. | ☐ | ☐ | |
| A3.2 | Live Chat | Lab Test tab → Live Chat. | Live chat screen opens. | ☐ | ☐ | |
| A3.3 | Chatbot | Lab Test tab → Chatbot. | Chatbot screen opens. | ☐ | ☐ | |
| A3.4 | Gemini Chatbot | Lab Test tab → Gemini Chatbot. | Gemini chat interface opens. | ☐ | ☐ | |
| A3.5 | ChatGPT | Lab Test tab → ChatGPT. | ChatGPT screen opens. | ☐ | ☐ | |
| A3.6 | Vital Organs | Lab Test tab → Vital Organs. | Vital organs test/list opens. | ☐ | ☐ | |
| A3.7 | Lab Test Screen | Lab Test tab → Select test / list. | Lab test list opens. | ☐ | ☐ | |
| A3.8 | Cart | Lab Test tab → Cart. | Lab cart opens. | ☐ | ☐ | |
| A3.9 | Health Package | Lab Test tab → Health Packages. | Health package list opens. | ☐ | ☐ | |
| A3.10 | PDF Viewer | Lab Test tab → any report/PDF. | PDF viewer opens. | ☐ | ☐ | |
| A3.11 | Web View | Lab Test tab → link that opens web view. | Web page opens in-app. | ☐ | ☐ | |

---

## A4. Report Tab

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| A4.1 | Report home | Tap **Report** tab at the bottom. | Report tab main screen opens. | ☐ | ☐ | |
| A4.2 | Online Link (2nd version) | Report tab → Online Link 2nd version. | Online report link page opens. | ☐ | ☐ | |
| A4.3 | SSL Success | Report tab → payment/link flow → Success. | SSL success page opens. | ☐ | ☐ | |
| A4.4 | Cancel Screen | Report tab → any cancel flow. | Cancel screen opens. | ☐ | ☐ | |
| A4.5 | Failed Screen | Report tab → failed flow (if testable). | Failed screen opens. | ☐ | ☐ | |
| A4.6 | PDF Viewer | Report tab → any report → PDF. | PDF viewer opens. | ☐ | ☐ | |
| A4.7 | Multi PDF | Report tab → multiple PDFs. | Multi PDF view opens. | ☐ | ☐ | |
| A4.8 | Report Detail | Report tab → report list → tap a report. | Report detail opens. | ☐ | ☐ | |
| A4.9 | Report Tracking | Report tab → Report Tracking. | Tracking screen opens. | ☐ | ☐ | |
| A4.10 | Web View | Report tab → web link. | Web view opens. | ☐ | ☐ | |

---

## A5. Service (AllService) Tab

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| A5.1 | Service home | Tap **Service** tab at the bottom. | Service main menu/card list opens. | ☐ | ☐ | |
| A5.2 | Online Service | Service tab → Online Service. | Online service screen opens. | ☐ | ☐ | |
| A5.3 | Lab Test | Service tab → Lab Test. | Lab test section opens. | ☐ | ☐ | |
| A5.4 | Home Call Service | Service tab → Home Call Service. | Home call service screen opens. | ☐ | ☐ | |
| A5.5 | Health Package | Service tab → Health Packages. | Health package list opens. | ☐ | ☐ | |
| A5.6 | Appointment / Department | Service tab → Appointment / Department. | Appointment or department list opens. | ☐ | ☐ | |
| A5.7 | Family Health Card | Service tab → Family Health Card. | Family Health Card opens. | ☐ | ☐ | |
| A5.8 | Hospital Branch | Service tab → General Hospital Branch. | Branch list opens. | ☐ | ☐ | |
| A5.9 | Full Body Checkup | Service tab → Full Body Checkup. | Full body checkup screen opens. | ☐ | ☐ | |
| A5.10 | Helpline | Service tab → Helpline. | Helpline opens. | ☐ | ☐ | |
| A5.11 | Ambulance | Service tab → Ambulance. | Ambulance booking opens. | ☐ | ☐ | |
| A5.12 | Pharmacy | Service tab → Pharmacy. | Pharmacy screen opens. | ☐ | ☐ | |
| A5.13 | Upcoming Feature | Service tab → Upcoming feature. | Upcoming feature message opens. | ☐ | ☐ | |
| A5.14 | General Service | Service tab → General Service. | General service opens. | ☐ | ☐ | |
| A5.15 | Physiotherapy | Service tab → Physio Therapy. | Physiotherapy screen opens. | ☐ | ☐ | |
| A5.16 | My Order | Service tab → My Order. | Order list opens. | ☐ | ☐ | |
| A5.17 | Cart | Service tab → Cart. | Cart opens. | ☐ | ☐ | |
| A5.18 | Doctor Booking Flow | Service tab → Doctor Appointment → list → slot → confirm. | Full doctor booking flow works. | ☐ | ☐ | |
| A5.19 | My Family | Service tab → My Family. | Family list opens. | ☐ | ☐ | |
| A5.20 | Chat (Live/Bot/Gemini/ChatGPT) | Service tab → any chat option. | Corresponding chat screen opens. | ☐ | ☐ | |
| A5.21 | IPD / OPD | Service tab → IPD or OPD. | IPD/OPD screen opens. | ☐ | ☐ | |
| A5.22 | IPD Feedback | Service tab → IPD → Feedback. | Feedback form opens. | ☐ | ☐ | |
| A5.23 | Cabin Patient | Service tab → Cabin Patient. | Cabin patient screen opens. | ☐ | ☐ | |
| A5.24 | Book Test | Service tab → Book Test. | Test booking flow opens. | ☐ | ☐ | |
| A5.25 | Lab Test / Vital Organs | Service tab → Lab Test or Vital Organs. | Corresponding screen opens. | ☐ | ☐ | |
| A5.26 | PDF / Web View | Service tab → report or link. | PDF or web view opens. | ☐ | ☐ | |
| A5.27 | Edit/Add Family | Service tab → My Family → Edit or Add. | Edit/Add member screen opens. | ☐ | ☐ | |
| A5.28 | Service Department | Service tab → Service Specialized Departments. | Service department list opens. | ☐ | ☐ | |

---

## A6. Profile Tab

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| A6.1 | Profile / My Account | Tap **Profile** tab at the bottom. | Profile home (My Account menu) opens; profile picture visible. | ☐ | ☐ | |
| A6.2 | My Details | Profile tab → My Details. | User details (name, phone, etc.) open. | ☐ | ☐ | |
| A6.3 | Saved Addresses | Profile tab → Saved Addresses. | Address list opens. | ☐ | ☐ | |
| A6.4 | Add New Address | Profile tab → Saved Addresses → Add New. | New address form opens. | ☐ | ☐ | |
| A6.5 | Edit Address | Profile tab → Saved Addresses → tap an address → Edit. | Edit address form opens. | ☐ | ☐ | |
| A6.6 | Help & Support | Profile tab → Help & Support. | Help/Support page opens. | ☐ | ☐ | |
| A6.7 | About Us | Profile tab → About Us. | About Us content opens. | ☐ | ☐ | |
| A6.8 | Notification | Profile tab → Notification. | Notification settings/list opens. | ☐ | ☐ | |
| A6.9 | PDF Viewer | Profile tab → any PDF link. | PDF viewer opens. | ☐ | ☐ | |
| A6.10 | My Order | Profile tab → My Order. | Order list opens. | ☐ | ☐ | |
| A6.11 | Single Order Detail | Profile tab → My Order → tap an order. | Order detail opens. | ☐ | ☐ | |
| A6.12 | Live Chat / Chatbot / Gemini / ChatGPT | Profile tab → any chat option. | Corresponding chat screen opens. | ☐ | ☐ | |
| A6.13 | Doctor Profile Edit | Profile tab → Doctor Edit Profile (for doctor user). | Doctor profile edit form opens. | ☐ | ☐ | |
| A6.14 | Doctor Profile View | Profile tab → Doctor Profile. | Doctor profile view opens. | ☐ | ☐ | |

---

# Part B — Drawer Menu

**How to open the drawer:** Tap the menu icon (☰) at the top/side of the screen. The drawer opens from the right.

---

## B1. Drawer — Home

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B1.1 | Home (from Drawer) | Open drawer → tap **Home**. | Drawer closes and Home tab opens; Home tab selected at bottom. | ☐ | ☐ | |

---

## B2. Drawer — My Profile

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B2.1 | My Profile (from Drawer) | Open drawer → tap **My Profile**. | Drawer closes and Profile section opens (My Account screen); Profile tab may be selected. | ☐ | ☐ | |
| B2.2 | My Account screen | Drawer → My Profile. | Profile index page (menu list) opens. | ☐ | ☐ | |
| B2.3 | Profile page / Details / Address | From Profile → any submenu. | Corresponding screen opens. | ☐ | ☐ | |

---

## B3. Drawer — Doctor Menu (Doctor users only — Permission: DoctorPanel)

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B3.1 | Doctor Menu home | Open drawer → tap **Doctor Menu**. (Must be logged in with doctor account.) | Doctor Menu home screen opens. | ☐ | ☐ | |
| B3.2 | Branch-wise patients | Doctor Menu → Branch wise patients. | Branch-wise patient list/UI opens. | ☐ | ☐ | |
| B3.3 | Patient List | Doctor Menu → Patient List. | Patient list opens. | ☐ | ☐ | |
| B3.4 | Doctor Chamber | Doctor Menu → Doctor Chamber. | Doctor chamber screen opens. | ☐ | ☐ | |
| B3.5 | Doctor Leave | Doctor Menu → Doctor Leave. | Leave request/UI opens. | ☐ | ☐ | |
| B3.6 | Morning Session | Doctor Menu → Doctor Chamber Morning. | Morning session screen opens. | ☐ | ☐ | |
| B3.7 | Evening Session | Doctor Menu → Doctor Chamber Evening. | Evening session screen opens. | ☐ | ☐ | |

---

## B4. Drawer — VMIS (Permission: Mobile.VMIS)

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B4.1 | VMIS menu | Open drawer → tap **VMIS**. (Account with VMIS permission.) | VMIS module screen opens. | ☐ | ☐ | |

---

## B5. Drawer — MR Menu (MR / Pharmaceutical user)

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B5.1 | MR Menu home | Open drawer → tap **MR Menu**. | MR menu home opens. | ☐ | ☐ | |
| B5.2 | MR Profile | MR Menu → MR Profile. | MR profile opens. | ☐ | ☐ | |
| B5.3 | Upload | MR Menu → Upload. | Upload screen opens. | ☐ | ☐ | |

---

## B6. Drawer — Appointment

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B6.1 | Appointment landing | Open drawer → tap **Appointment**. | Specialized Department / Appointment landing page opens. | ☐ | ☐ | |

---

## B7. Drawer — Services

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B7.1 | Service tab (from Drawer) | Open drawer → tap **Services**. | Drawer closes and Service tab opens; Service tab selected at bottom. | ☐ | ☐ | |

---

## B8. Drawer — My Health Record

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B8.1 | Health Record home | Open drawer → tap **My Health Record**. | Health Record home screen opens. | ☐ | ☐ | |
| B8.2 | Image Gallery | My Health Record → Image Gallery. | Health record image gallery opens. | ☐ | ☐ | |
| B8.3 | Single Image View | My Health Record → tap an image. | Single image view (HealthRecordShowImage) opens. | ☐ | ☐ | |

---

## B9. Drawer — My Health Card

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B9.1 | Health Card | Open drawer → tap **My Health Card**. | Health Card screen opens. | ☐ | ☐ | |

---

## B10. Drawer — Delivery (Permission: HomeCallServiceMan)

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B10.1 | Delivery home | Open drawer → tap **Delivery**. (Account with delivery permission.) | Delivery home (Deliverable/Delivered tab or list) opens. | ☐ | ☐ | |
| B10.2 | Single delivery info | Delivery → tap a delivery item. | Single delivery detail opens. | ☐ | ☐ | |
| B10.3 | Deliverable list | Delivery → Deliverable. | Deliverable item list opens. | ☐ | ☐ | |
| B10.4 | Delivery Scanner | Delivery → Scanner. | Scanner screen opens. | ☐ | ☐ | |
| B10.5 | Delivery OTP | Delivery → OTP flow. | OTP input screen opens. | ☐ | ☐ | |
| B10.6 | Delivered list | Delivery → Delivered. | Delivered item list opens. | ☐ | ☐ | |
| B10.7 | Delivered item detail | Delivery → Delivered → tap an item. | Single delivered info opens. | ☐ | ☐ | |

---

## B11. Drawer — Share App

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B11.1 | Share App | Open drawer → tap **Share App**. | Share dialog (system share sheet) opens; app link and message are present. | ☐ | ☐ | |

---

## B12. Drawer — Logout

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| B12.1 | Logout confirm | Open drawer → tap **Logout**. | "Are you sure you want to logout?" alert appears. | ☐ | ☐ | |
| B12.2 | Logout Yes | Logout → tap **Yes**. | Logout loading shows; then redirects to Sign-in screen. | ☐ | ☐ | |
| B12.3 | Logout Cancel | Logout → tap **Cancel**. | Alert dismisses; app stays logged in. | ☐ | ☐ | |

---

# Part C — General (check across the app)

| # | Test Case | Steps (How to get there) | Expected Result (What you should see) | Pass | Fail | Notes |
|---|-----------|---------------------------|----------------------------------------|------|------|-------|
| C1 | Status bar colour | Go to any screen. | Top status bar is green (#3BB54A) or per app theme. | ☐ | ☐ | |
| C2 | Back button | Go to any sub-screen → tap back button. | Returns to previous screen; no crash. | ☐ | ☐ | |
| C3 | Tab and Drawer sync | Go to any tab → open drawer. | Drawer highlights the item matching current tab/page. | ☐ | ☐ | |
| C4 | Drawer by permission | Log in with different roles (Patient, Doctor, Delivery, MR). | Drawer shows only items allowed for that role. | ☐ | ☐ | |
| C5 | Profile picture (tab bar) | Log in with account that has profile picture set. | Profile tab at bottom shows user photo (not placeholder). | ☐ | ☐ | |
| C6 | Keyboard and tab bar | Tap any input field to open keyboard. | Tab bar may hide (per app design). | ☐ | ☐ | |

---

**Notes for QA Team**  
- Read through the full checklist once before testing a new build.  
- If you cannot find a screen, double-check the **Steps** (menu names may differ in the app).  
- When marking **Fail**, briefly note in **Notes** what went wrong (e.g. "Screen does not open", "Crash").  
- Test permission-based drawer items (Doctor Menu, VMIS, MR Menu, Delivery) with the relevant role accounts.

---

*Document version: 1.0 — QA Test Checklist for Health Connect Mobile*
