# P-Wagon
P-Wagon is an innovative product designed to assist law enforcement agencies in combating crime through real-time analysis of live footage. Utilizing the compact yet powerful Raspberry Pi 4, P-Wagon captures video streams from surveillance or car dash cameras and processes them using  machine learning algorithms.

## Core Functionality

At the core of P-Wagon's functionality is an object detection algorithm specifically tailored to recognize vehicle license plates. Once a license plate is detected in the footage, the image is passed through Optical Character Recognition (OCR) technology, powered by Google, to extract the alphanumeric characters of the plate.

## Backend Integration

The extracted license plate information is then sent to a backend system, where it is matched against a database of vehicles of interest. This could include stolen vehicles, vehicles associated with missing persons, or vehicles involved in ongoing investigations. When a match is found, the system updates the alert status, which can also be initiated or managed through a user-friendly frontend interface.

## Impact on Public Safety

P-Wagon's real-time processing and alert system enable authorities to respond swiftly to potential threats or criminal activities, enhancing public safety and security. By integrating advanced technologies like machine learning and OCR, P-Wagon offers a powerful tool for law enforcement agencies to stay ahead in the fight against crime.

## Technology Used

- **Raspberry Pi**: Utilized for capturing live footage from surveillance cameras.
- **NextJS**: Powers the frontend interface for managing alerts and viewing live feeds.
- **Google Firebase - Realtime Database**: Used as the database for storing and retrieving vehicle information and alerts.
- **Python Flask Server**: Serves as the backend server for handling requests between the frontend and the RaspberryPi
- **Python for Machine and Deep Learning**: Used for developing and implementing the object detection 
