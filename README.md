# Lab 12

This Flutter application demonstrates basic Firestore functionalities for handling data - saving and reading data to/from Firestore.

Ony allowed messages:     **^((?i)hello|\\s|firebase|welcome|to|summit|the|this|everyone|good|morning|afternoon|firestore|meetup|devfest|virtual|online)+**

## Overview

The application consists of two primary screens:
1. **Save Data to Firestore**: Allows users to input text data and saves it to Firestore by pressing the "Save to Firestore" button.
2. **Read Data from Firestore**: Retrieves and displays the stored text data from Firestore in a list view.

## Implementation Details

### Save Data to Firestore Screen
- Provides a text field for users to input data.
- Saves the entered data to Firestore upon button press.

### Read Data from Firestore Screen
- Retrieves data from Firestore and displays it in a scrollable list view.
- Data is sorted based on the timestamp when it was added.

## Usage

1. Run the app on an emulator or physical device.
2. Use the "Save Data to Firestore" screen to input and save data.
3. Use the "Read Data from Firestore" screen to view the stored data.

