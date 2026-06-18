# Firebase_Image_Upload_App

This is an Android application developed using Java and Firebase. The application allows users to select an image from the device gallery, upload it to Firebase Storage, save the image details in Firestore, and automatically display the uploaded image and its information.

## 🚀 Features

- 📁 Select an image from the gallery
- 👀 Preview selected image
- ☁️ Upload image to Firebase Storage
- 💾 Save image details to Firebase Firestore
- 🔗 Display image download URL
- 🖼️ Automatically display the latest uploaded image
- 📅 Show upload date and time
- 📊 Upload progress indicator
- ⚠️ Error handling and success messages

---

## 🛠️ Technologies Used

- Java
- Android Studio
- Firebase Storage
- Firebase Firestore
- Glide Image Library
- ConstraintLayout

---

## 📸 Workflow

```
Select Image
      │
      ▼
Preview Image
      │
      ▼
Upload to Firebase Storage
      │
      ▼
Get Download URL
      │
      ▼
Save Details in Firestore
      │
      ▼
Display Image + Name + URL + Upload Time
```

---

## 📊 Firestore Structure

```
ImageInfo
│
├── documentID
│     ├── imageName
│     ├── imageUrl
│     ├── uploadedAt
│     └── timestamp
```

---

## 📦 Dependencies

- Firebase Firestore
- Glide



