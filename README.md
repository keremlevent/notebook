# 🍽️ Recipe Notebook

**Recipe Notes** is a modern Android app that allows users to save recipes. 

---

## 🚀 Features

- ✅ Add, edit, and delete recipes
- ✅ Save ingredients, instructions, and photos for each recipe


---

## 🛠️ Built With

- **Kotlin**
- **Room (SQLite database)**
- **RecyclerView**
- **RxJava**

---

## 📸 Screenshots

<p align="center">
  <img src="screenshots/list.png" alt="Recipe List" width="45%" />
  &nbsp;&nbsp;
  <img src="screenshots/recipe.png" alt="Add Recipe" width="45%" />
</p>


---

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/recipe-notes.git
   ```

2. **Open in Android Studio**

3. **Build and Run**
   - `Build > Rebuild Project`
   - Run on emulator or physical device

> **Minimum SDK:** 23 (Android 6.0)  
> **Target SDK:** 34 (Android 14)

---

## 🧠 Architecture Overview

This project follows **MVVM (Model-View-ViewModel)** architecture:

- `Model`: Data classes and Room database
- `ViewModel`: Lifecycle-aware data handling
- `View`: Fragments and Activities using LiveData for UI updates

---

## 📁 Project Structure

```
├── data/
│   ├── model/
│   ├── dao/
│   └── database/
├── ui/
│   ├── fragments/
│   ├── viewmodels/
│   └── adapters/
├── utils/
├── MainActivity.kt
```

---

## ✍️ Author

**Your Full Name**  
📧 [your.email@example.com](mailto:your.email@example.com)  
🔗 [LinkedIn Profile](https://linkedin.com/in/yourusername)  
🔗 [GitHub Profile](https://github.com/yourusername)

---

## 📄 License

This project is licensed under the MIT License – see the `LICENSE` file for details.

---

## 🙌 Contributions

Pull requests are welcome! Feel free to fork the project and submit improvements or suggestions.
