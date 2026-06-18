# Firebase_Image_Upload_App

This is an Android application developed using Java and Firebase. The application allows users to select an image from the device gallery, upload it to Firebase Storage, save the image details in Firestore, and automatically display the uploaded image and its information.

## 🚀 Features

- ✅ Select image from gallery
- ✅ Upload image to Firebase Firestore (No Firebase Storage required!)
- ✅ Images stored as Base64 strings
- ✅ Display latest uploaded image
- ✅ Progress bar for upload status
- ✅ No external hosting services needed (ImgBB, Cloudinary, etc.)
- ✅ Works with Firestore free tier (1MB document limit)

---

## 🛠️ Technologies Used

- **Android Studio** - IDE
- **Java** - Programming Language
- **Firebase Firestore** - NoSQL Database

---

## 📋 Prerequisites

Before you begin, ensure you have:

1. **Android Studio** installed
2. **Firebase Account** (free tier works!)
3. **Firebase Project** created
4. **google-services.json** file downloaded

---

## 📸 Workflow

```
Select Image
      │
      ▼
Preview Image
      │
      ▼
Save Details in Firestore
      │
      ▼
Display Image + Name + URL + Upload Time


---

## 📊 Firestore Structure


ImageInfo
│
├── documentID
│     ├── imageName
│     ├── imageUrl
│     ├── uploadedAt
│     └── timestamp
```







