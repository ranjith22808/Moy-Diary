📔 Moy Diary - Digital Personal Ledger System
Moy Diary is a modern, high-performance web application designed to digitize the traditional "Moy" (social gift) accounting system. It helps users track cash and gold gifts received or given during family functions and social events with precision and ease.

✨ Key Features
Vibrant & Modern UI: A colorful, mobile-first design built with a focus on user experience.

Dual Tracking (Cash & Gold): Simultaneously manage both monetary gifts and gold ornaments (in grams).

Smart Tally & Balance Logic:

Automatically calculates totals for specific individuals or events.

Smart labels: To Give (Obligation) or To Receive (Extra/Pre-paid) for clear financial standing.

Intelligent Search & Analytics: Filter records by Name, Area, or Event Name to get instant summaries.

Duplicate Entry Prevention: Built-in validation to alert users if a person is being registered twice for the same event.

Dynamic Auto-Suggestions: Remembers previously entered Names, Areas, and Events to speed up data entry.

One-Click Excel Export: Download filtered or full reports as .xlsx files with dynamic, search-based filenames.

Auto-Formatting: Automatically capitalizes the first letter of each word (Proper Case) while typing for consistent data entry.

🛠️ Tech Stack
Frontend: HTML5, Tailwind CSS (Modern UI Framework), JavaScript (ES6+).

Database: Firebase Firestore (Real-time Cloud Database).

Excel Engine: SheetJS (XLSX) for professional report generation.

Typography: Google Fonts (Poppins & Inter).

🚀 How to Get Started
Save the File: Download the source as an .html file.

Configuration: Replace the firebaseConfig object in the script section with your own Firebase project credentials.

Deployment: Open the file in any modern browser or host it on GitHub Pages / Firebase Hosting as a PWA.

Usage: * Set the Event Name and Date (these remain sticky for fast entries).

Enter the Name, Area, and Amount.

Hit SAVE.

Use the Search Bar to instantly calculate balances for any person or function.

📂 Database Schema
Records are stored in the moy_records collection with the following structure:

JSON

{
  "name": "Ranjith Kumar",
  "city": "Cuddalore",
  "cash": 500,
  "gold": 2.5,
  "type": "Received",
  "event": "Marriage Reception",
  "notes": "Gifted with a silk shawl",
  "date": "2026-03-25"
}
👨‍💻 Developed By
Ranjithkumar R Web Developer | Founder, Matisha Infotec 📍 Cuddalore, Tamil Nadu, India


📔 Moy Diary - Personal Ledger System
Moy Diary என்பது பாரம்பரிய "மொய்" கணக்கு முறையை டிஜிட்டல் மயமாக்கும் ஒரு நவீன வலைப்பயன்பாடு (Web App) ஆகும். இது விசேஷங்களில் பெறப்படும் மற்றும் திரும்பச் செலுத்தப்படும் பணம் மற்றும் தங்கக் கணக்குகளைத் துல்லியமாக நிர்வகிக்க உதவுகிறது.

✨ சிறப்பம்சங்கள் (Features)
Vibrant & Modern UI: பயனர் எளிதில் கையாளும் வகையில் வண்ணமயமான மற்றும் நவீனத் தோற்றம்.

Dual Tracking: பணம் (Cash) மற்றும் தங்கம் (Gold) இரண்டையும் ஒரே நேரத்தில் கணக்கிடும் வசதி.

Smart Tally & Balance: * ஒவ்வொரு நபரின் வரவு மற்றும் செலவைத் தானாகவே கூட்டும்.

To Give (தர வேண்டியது) அல்லது To Receive (வர வேண்டியது) எனப் பாக்கித் தொகையைத் துல்லியமாகக் காட்டும்.

Intelligent Search: பெயர் (Name), ஊர் (Area) அல்லது விசேஷத்தின் பெயர் (Event) மூலம் தேடும் வசதி.

Data Deduplication: ஒரே விசேஷத்தில் ஒரு நபர் இரண்டு முறை பதிவு செய்யப்படுவதைத் தடுக்கும் எச்சரிக்கை வசதி.

Auto Suggestions: முன்பு பதிவு செய்த பெயர், ஊர் மற்றும் விசேஷப் பெயர்களைத் தானாகவே பரிந்துரைக்கும் (Autocomplete).

Excel Export: தேடப்பட்ட விவரங்களை அல்லது முழு டேட்டாவை டைனமிக் ஃபைல் பெயருடன் எக்ஸெல் கோப்பாக டவுன்லோட் செய்யும் வசதி.

Proper Casing: டைப் செய்யும் போதே தானாகவே வார்த்தையின் முதல் எழுத்தைப் பெரிய எழுத்தாக (Capitalize) மாற்றும் வசதி.

🛠️ தொழில்நுட்பங்கள் (Tech Stack)
Frontend: HTML5, Tailwind CSS (Styling), JavaScript (ES6+).

Backend/Database: Firebase Firestore (Real-time Cloud Database).

Libraries: * Firebase JS SDK - டேட்டா சேமிப்பிற்கு.

SheetJS (XLSX) - எக்ஸெல் டவுன்லோட் வசதிக்கு.

Google Fonts - Poppins எழுத்துருவிற்கு.

🚀 பயன்படுத்துவது எப்படி? (How to Use)
இந்தக் கோப்பை ஒரு .html ஃபைலாகச் சேமிக்கவும்.

உங்களுடைய Firebase Config விவரங்களை ஸ்கிரிப்ட் பகுதியில் உள்ள firebaseConfig மாறியில் (Variable) இணைக்கவும்.

எந்தவொரு பிரவுசரிலும் (Browser) இந்தப் ஃபைலைத் திறக்கவும்.

முதலில் ஒரு விசேஷத்தின் பெயரை (Event Name) உள்ளிடவும்.

நபரின் பெயர், ஊர் மற்றும் தொகையைப் பதிவு செய்து 'SAVE' பட்டனை அழுத்தவும்.

தேவைப்படும்போது தேடல் கட்டத்தில் (Search Bar) பெயரைத் தட்டச்சு செய்து பாக்கி விவரங்களைக் காணலாம்.

📂 டேட்டா அமைப்பு (Database Structure)
ஒவ்வொரு பதிவும் moy_records என்ற கலெக்ஷனில் கீழ்வரும் வடிவில் சேமிக்கப்படும்:

JSON

{
  "name": "Ranjith Kumar",
  "city": "Cuddalore",
  "cash": 500,
  "gold": 2.0,
  "type": "Received",
  "event": "Wedding",
  "notes": "With Silk Saree",
  "date": "2026-03-25"
}
👨‍💻 உருவாக்கியவர் (Developed By)
Ranjithkumar R Web Developer | Matisha Infotec# Moy Diary
Moy details of my function 
