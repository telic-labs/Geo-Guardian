# GeoGuardian

GeoGuardian is a service that allows administrators to locate their users. It uses a Linux PAM module to request the user's location for privileged actions such as login and `sudo`. 
Users scan a QR code displayed on the terminal with the GeoGuardian mobile app to approve the login or privileged action. 
The user's geolocation is measured at the time the QR code is scanned and then reported back to the PAM module. 
The administrator may choose to configure PAM to report the location only, or to enforce operation within certain "safe zones".

## 👥 Features

- User location verification or monitoring at logon and for privileged actions (PAM facilitated).
- QR code-based process via the GeoGuardian mobile app.
- Real-time geolocation reporting to the PAM module when QR code are requested and scanned.
- Integration with Linux PAM for seamless authentication or reporting.

## 📷 Example

Below is an example of what a terminal-based QR code could look like:
![Terminal QR Code](https://github.com/telic-labs/Geo-Guardian/blob/main/term.jpeg)


## 📞 Support

If you need assistance or have any questions, please reach out to us:

- **Email:** [developer@telic.co.za](mailto:developer@telic.co.za)
- **Report an Issue:** [GitHub Issues](https://github.com/telic-labs/Geo-Guardian/issues)
- **Privacy Policy:** [View Here](https://github.com/telic-labs/Geo-Guardian/blob/main/privacy-policy.txt)


### ❓ Frequently Asked Questions

**Q:** How do I ...?  
**A:** The service is currently in the beta stage. All users are requested to direct all queries or comments to the support email address.

## 🕒 Support Hours

- **Email Support:** Best effort basis. Please allow some time for a response.

## 👥 Contributing

We welcome contributions to improve GeoGuardian. Feel free to submit issues or pull requests via GitHub.

## 📲 App Download

[Android](https://play.google.com/store/apps/details?id=za.co.telic.geoguardian&hl=en)

---

Thank you for using GeoGuardian!
