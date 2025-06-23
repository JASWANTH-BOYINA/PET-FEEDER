# PET-FEEDER
Several existing systems allow pet owners to feed their pets remotely, including automated pet feeders that work via mobile apps, cameras, and sensors. These devices typically use Wi-Fi, Bluetooth, or RFID technology to control the feeder, and they often require custom-built software or hardware. However, many commercial solutions are expensive and lack customization.
The use of IFTTT is to integrate web services like Google Assistant with Arduino-based systems has been explored in various DIY projects. IFTTT simplifies the automation of smart home devices, and Arduino’s versatility makes it an ideal platform for such applications. For example, similar projects include voice-controlled devices, IoT-based home automation, and voice-assisted pet care systems, but most are based on specific cloud services or require extensive coding knowledge. This project combines affordable hardware components and widely accessible platforms like IFTTT to create a simple, effective, and customizable solution for pet care.
_____

## Work Flow:
**1. Scheduled Feeding**

 - Trigger: Set daily/weekly feeding times using IFTTT’s scheduling.
 - Action: Activate the pet feeder at specific times (e.g., 7 AM, 6 PM).
 - Service used: Date & Time + Webhooks.

**2. Voice Control via Smart Assistant**

 - Trigger: Voice command through Alexa, Google Assistant, or Siri.
 - Action: Dispense food.
 - Service used: Google Assistant/Alexa + Webhooks.

**3. Mobile App Control**

 - Trigger: Button press on the IFTTT app (on your phone).
 - Action: Feed your pet remotely.
 - Service used: IFTTT App Button widget + Webhooks.

**4. Low Food Notification**

 - Trigger: Pet feeder detects low food level (via sensor).
 - Action: Send an SMS, email, or phone notification.
 - Service used: Webhooks + Notifications/SMS/Email.

**5. Pet Feeding Log**

 - Trigger: Every time food is dispensed.
 - Action: Log data to Google Sheets or send an email.
 - Service used: Webhooks + Google Sheets/Email.
______

## Applications:

 1. Automated Feeding
 2. Remote Feeding Control
 3. Smart Home Integration
 4. Feeding Activity Logging
 5. Food Level Monitoring & Alerts
 6. Monitoring Feeding Behavior
 7. Location-Based Feeding
 8. Multi-User Notifications
 9. Health & Dietary Management
 10. Developer & Maker Use
_______

## Getting Ready
   - Install necessary libraries in arduino IDE.
   - Dump the code and integrate IFTTT and google assistant to start.
