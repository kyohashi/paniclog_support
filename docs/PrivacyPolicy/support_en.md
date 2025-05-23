# Panic Log Support Page

Thank you for using the Panic Log app. We hope this page helps answer your questions and resolve any issues you may encounter.

---

## Frequently Asked Questions (FAQ)

### Basic Usage

**Q: How do I use Panic Log?**  
A: The Panic Log app primarily offers four functions:

  * **Logging Feature**: Record anxiety attacks in real-time, including duration, symptom intensity, weather, tags, coping mechanisms and their effects, and notes.
  * **Mood Tracking Feature**: Track your daily mood with scores and comments to monitor fluctuations.
  * **Analysis Feature**: View your recorded anxiety attacks and mood data in a calendar format or statistical graphs to analyze your personal patterns.
  * **Data Management**: Centrally manage all your records and review the effects of symptoms and coping strategies. By creating an account, you can securely save your data to the cloud and sync it across multiple devices.

**Q: How do I log an anxiety attack?**  
A: Tap the "Start Panic Attack Log" button on the home screen to begin the timer. Once the attack subsides, tap "Complete Log" and enter the details (intensity, coping mechanisms, tags, etc.).

**Q: How do I log my mood?**  
A: Tap the mood icon (face icon) in the top-right corner of the home screen, or open the mood logging screen from a set reminder notification, then enter your daily mood score and comments and save.

**Q: Can I edit my records?**  
A: Yes. Select a date from the calendar on the home screen, then tap on the displayed anxiety attack log or mood log to open the editing screen. You can modify the start/end times, intensity, coping mechanisms, notes, and more at any time.

---

### Data and Storage (Account Linking)

**Q: Where is my data saved?**  
A:
  * **If you are not registered (anonymous use)**: All your data is saved only on your iOS device.
  * **If you are registered and logged in**: Your data is securely saved to Firebase Firestore (cloud) and also cached on your device's local storage. This allows you to view, add, and edit records offline, and they will automatically sync when you are online.

**Q: What are the benefits of creating an account?**  
A: Creating an account and logging in offers the following benefits:
  * **Data Sync**: Sync your records across multiple iOS devices.
  * **Data Backup**: Restore your data from the cloud when changing devices or reinstalling the app.
  * **Data Protection**: Reduce the risk of losing your valuable records in case of device loss or malfunction.

**Q: What happens to my local data recorded before I create an account?**  
A: The first time you register an account or log in, if previous record data (anonymous data) exists on your device, you will be presented with the following options:
  * **"Migrate and merge existing local data into the new account"**: Your local data will be uploaded to the new account and remain accessible.
  * **"Discard local data and use cloud data (or empty data)"**: Your local data will be deleted, and data from your new account (if any) will be used.

Please choose based on your situation. We recommend selecting carefully to avoid accidental data loss.

**Q: What happens to my data if I log out?**  
A: When you log out, data associated with that account is cleared from your device's local storage to protect your privacy. If you log in with the same account again, your data will sync from the cloud. If you continue to use the app after logging out, any new data will temporarily be saved locally.

**Q: How is my data backed up?**  
A:
  * **For registered account users**: Your data is automatically backed up and synced to Firebase Firestore (cloud). No special operations are required.
  * **For unregistered users**: Your data is included in your iOS device's standard backups (iCloud or local backup via iTunes/Finder). We recommend regular device backups.

**Q: What happens to my data if I delete the app?**  
A:
  * **For registered account users**: Even if you delete the app, your data is saved in the cloud. You can restore your data by logging in with the same account again.
  * **For unregistered users**: Deleting the app will also delete your local data on the device. Unless you restore from a previous iOS device backup, your data will not return after reinstalling the app.

---

### Permissions and Settings

**Q: What permissions does the app request?**  
A: Panic Log may request the following permissions to provide a better experience:
  * **Notifications (Optional)**: Used to receive daily mood logging reminders and other app announcements.

All permissions are optional, and the app's core functions can be used even if permissions are not granted. You can change permission settings anytime from your iOS "Settings" app.

---

### Troubleshooting

**Q: What should I do if the app crashes unexpectedly?**  
A: Please try the following steps:
  1.  Close other running apps, then restart Panic Log.
  2.  Restart your iOS device.
  3.  Check if the Panic Log app is updated to the latest version on the App Store.
  4.  If the issue persists, try deleting and reinstalling the app.
      * **For registered account users**: After reinstalling, your data will be restored by logging in with the same account.
      * **For unregistered users**: Your data may be lost, so if possible, consider backing up your iOS device beforehand.

**Q: My time logging doesn't seem to be working correctly.**  
A: Please check the following:
  1.  Confirm that your iOS device's date and time settings are accurate ("Settings" app > "General" > "Date & Time").
  2.  If the issue persists after restarting the app, try restarting your iOS device.

**Q: Data is not showing up on the statistics screen.**  
A:
  1.  To display statistics, you need at least one anxiety attack log or mood log record. If you don't have any records yet, please create some from the home screen.
  2.  If records exist but are not displayed, first try restarting the app.
  3.  **If you are using an account**: Data synchronization may be taking time, or there might be a temporary communication error. Tap the manual sync button (circular arrow icon) in the account information area of the "Settings" tab to try re-syncing your data. Please wait for a moment until the sync is complete.
  4.  If it still doesn't show up, please check if the time range filter (e.g., "1 Month," "3 Months") is unintentionally set to an incorrect period.

**Q: My data doesn't seem to be syncing correctly.**  
A:
  1.  Ensure you have a stable internet connection (Wi-Fi or cellular data).
  2.  Check the "Last Synced Time" displayed in the account information area of the "Settings" tab.
  3.  Tap the manual sync button (circular arrow icon) to try re-syncing your data. "Syncing..." will be displayed during the synchronization process.
  4.  Completely closing and restarting the app may retry the synchronization.
  5.  Restarting your device can also be effective.

If the problem persists after trying the above, please contact us.

---

## Contact Us

If you have any technical issues or questions, please contact us using the methods below:

- [Form](https://forms.gle/je7u4qhwCDQAeUym8)

---

## Privacy Policy

For information about the app's privacy policy, please see here:
- [Privacy Policy](https://kyohashi.github.io/paniclog_support/PrivacyPolicy/privacy_en)

---

**Important**: This app does not provide medical advice. If you are experiencing severe symptoms, please consult a medical professional. Panic Log is intended to help you record and better understand your own condition.