# SecurSight Android App

## Description
SecurSight is an advanced object detection system designed to enhance security in crowded areas. By integrating with existing CCTV infrastructure, SecurSight identifies human body movements and generates alerts to ensure public safety. The system features a dynamic map interface displaying areas covered by CCTVs, capable of stretching up to 1-2 kilometers, and allows seamless setup of continuous CCTV streams.

## Features

### Feature 1: Weapon Detection
- **Description:** Detects weapons in CCTV footage.
- **Action:** Generates an alert marking the coordinates in the app.
- **Notification:** Automated call and SMS to concerned authorities.
- **Data Storage:** Stores camera ID, timestamp, and photograph for reference.

### Feature 2: Fight Detection
- **Description:** Recognizes human figures fighting using body posture recognition.
- **Action:** Generates an appropriate alert.
- **Data Storage:** Stores camera ID, timestamp, and photograph for reference.

### Feature 3: Video Storage (Optional)
- **Description:** Stores a 2-5 minute video in Firebase for future reference and model training.
- **Action:** Allows coordinates to be marked and stored as video clips.
- **Note:** This feature is optional and subject to confirmation.

### Feature 4: Temperature Detection and Fire Alerts
- **Description:** Detects temperature anomalies and potential fires.
- **Action:** Generates an alert to authorities upon fire detection.
- **Data Storage:** Stores camera ID, timestamp, and photograph for reference.

### Feature 5: Telegram Bot Integration (Optional)
- **Description:** Utilizes a Telegram bot to store unusual events recorded by the model.
- **Action:** Creates patterns from recorded events to predict potential mishaps.
- **Sharing:** Shares information safely with users.
- **Note:** This feature is optional and subject to further development.

## Key Focus
- **Map Integration:** A single integration accommodating every region, eliminating the need for multiple apps or integrations for different places.
- **Authentication Page:** Optional and to be developed post-hackathon.

## Future Improvements
- Features can be improvised to enhance efficiency and effectiveness over time.
