[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z01C2S57)

## 🎟️ Why WebNFCVCard 
When attending a conference, you meet many new people and make valuable connections. A quick and efficient way to exchange contact information without wasting time is by using a vCard. 

A `vCard` is a standardized format for electronic business cards, essentially a structured text file. (See [vCard on Wikipedia](https://en.wikipedia.org/wiki/VCard) for more details.) 

There are two common ways to share a vCard at a conference:
1. **Via QR Code** – The organizer collects attendee data and prints a QR code on the badge. (that contain a vCard!)
2. **Using an NFC Tag** – Attendees receive an NFC tag as swag and use a tool to write their own vCard onto it.

The first option is also very simple but requires some effort from the organizing team. The major disadvantage is that you cannot modify or update the data inside the vCard.

The second option involves a cost (as you need to purchase NTAG), but it allows you to delegate the creation of the vCard to the attendee. This way, the attendee can update their data and reuse it at other conferences.

### 🌐 Why Use a Web Page? 
With a web-based tool, you can access the vCard writing feature directly without needing to install an app. This makes the process extremely fast and convenient! 

## 🛠️ Technology Behind WebNFCVCard 
WebNFCVCard leverages the **Web NFC API** ([MDN documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_NFC_API)), an experimental API that allows web pages to interact with NFC tags. While not all browsers support this API, **many users have Chrome on their smartphones**, making it widely accessible. 📱💻✅

### Compatibility 
TL;DR Only Android support Web NFC API on Chrome (89), Opera (63) and Samsung Internet (15.0)

### Usage 
Once you vCard in written in the NFC tag you can scan it with and add automatically the contact on your phonebook. Unfortunately iOS doesn't support it.

## 🤗 Contributions 
Contributions are always welcome! If you need to customize this project for your event, feel free to fork it and make it your own.

## 🤙 Support the project 
If you’d like to support this small yet useful project, click here: [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z01C2S57)

If you’re a company organizing events and need a customized version of WebNFCVCard, feel free to reach out to me on LinkedIn.

## To-Do List 📝
- Add complete support for vCard 2.1 , 3.0, 4.0
- Improve the user interface (UI) for a better experience.
- Display the size of the content being written to the NFC tag (since different NFC types have varying memory limits).
- Add more fields based on the vCard specification.

Your feedback and contributions are highly appreciated! 💬

## License
MIT License
