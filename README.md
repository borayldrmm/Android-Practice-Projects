# 🚀 Android Practice Projects

A collection of Android applications built during my learning journey, demonstrating various concepts, architectures, and technologies in Android development.

> **Note:** These projects were created as part of my Android learning process. For production-ready work, please see my featured projects: [FoodieHub](https://github.com/borayldrmm/FoodieHub) and [BeautyDate](https://github.com/borayldrmm/BeautyDate).

---

## 📚 Projects Overview

### 🎮 Game & Interactive Apps
| Project | Description | Tech Stack |
|---------|-------------|------------|
| [CatchTheKenny](#catchthekenny) | Simple reaction game with timer | Kotlin, View Binding, Handlers |
| [SimpleStopwatch](#simplestopwatch) | Functional stopwatch application | Kotlin, Chronometer, UI Components |

### 🌐 API Integration Practice
| Project | Description | Tech Stack |
|---------|-------------|------------|
| [RetrofitKotlin](#retrofitkotlin) | Advanced cryptocurrency tracker with RxJava | Retrofit, RxJava3, RecyclerView, CompositeDisposable |
| [CryptoWalletApp](#cryptowalletapp) | Cryptocurrency price tracker with Coroutines | Retrofit, Coroutines, RecyclerView |
| [JokeApp](#jokeapp) | Random joke fetcher | Retrofit, JSON parsing, API integration |

### 📱 UI & Database Practice
| Project | Description | Tech Stack |
|---------|-------------|------------|
| [ArtbookNavFragment](#artbooknavfragment) | Art gallery with modern navigation (v2) | Navigation Component, Room, Fragments |
| [ArtBookProject](#artbookproject) | Art gallery with classic approach (v1) | SQLite, Activity, RecyclerView |
| [ShoppingList](#shoppinglist) | Shopping list with local storage | Room Database, MVVM, RecyclerView |
| [TravelBook](#travelbook) | Location saving app with maps | Google Maps API, Room, SQLite |
| [SuperheroBook](#superherobook) | Superhero database browser | Room, RecyclerView, CRUD operations |

### 📸 Clone Projects
| Project | Description | Tech Stack |
|---------|-------------|------------|
| [CloneInstagram](#cloneinstagram) | Instagram-like social app | Firebase Auth, Firestore, Storage |

---

## 🛠️ Technologies Used Across Projects

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-009688?style=flat)
![Room](https://img.shields.io/badge/Room-4285F4?style=flat)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=flat)

- **Languages:** Kotlin
- **Architectures:** MVVM, basic MVC
- **UI:** XML Views, View Binding, RecyclerView
- **Networking:** Retrofit, Coroutines
- **Local Storage:** Room Database, SQLite, SharedPreferences
- **Firebase:** Authentication, Firestore, Storage
- **Maps:** Google Maps SDK
- **Navigation:** Navigation Component, Fragments

---

## 📖 Project Details

### CatchTheKenny
**Description:** A simple reaction-based game where users tap on randomly appearing Kenny characters within a time limit.

**Key Features:**
- Timer-based gameplay
- Score tracking
- Random image positioning
- Handler for UI updates

**Tech Stack:** Kotlin, View Binding, Handlers, ImageView animations

**Learning Focus:** Android Handlers, UI manipulation, game loop basics

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/catchTheKenny)

---

### TravelBook
**Description:** An application to save and display travel locations on an interactive map.

**Key Features:**
- Google Maps integration
- Save locations with coordinates
- Room database for persistence
- Custom map markers

**Tech Stack:** Kotlin, Google Maps API, Room, SQLite, RecyclerView

**Learning Focus:** Google Maps SDK, location services, database integration

[📂 View Code](https://github.com/Android-Practice-Projects/myProjects/tree/main/TravelBook)

---

### SuperheroBook
**Description:** A superhero database application with CRUD operations.

**Key Features:**
- List superhero data from Room database
- Add/Edit/Delete superheroes
- RecyclerView with click handling
- Image storage integration

**Tech Stack:** Kotlin, Room Database, RecyclerView, CRUD operations

**Learning Focus:** Room database operations, RecyclerView adapters, data persistence

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/SuperheroBook)

---

### ShoppingList
**Description:** A shopping list manager with local storage.

**Key Features:**
- Add/remove shopping items
- Persistent storage with Room
- MVVM architecture pattern
- RecyclerView with item decoration

**Tech Stack:** Kotlin, Room, MVVM, LiveData, RecyclerView

**Learning Focus:** MVVM architecture, Room database, reactive UI with LiveData

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/ShoppingList)

---

### JokeApp
**Description:** Fetches random jokes from a public API.

**Key Features:**
- REST API integration
- JSON parsing
- Retrofit + Coroutines
- Display API responses

**Tech Stack:** Kotlin, Retrofit, Coroutines, JSON, RecyclerView

**Learning Focus:** REST API consumption, Retrofit setup, asynchronous programming

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/JokeApp)


---

### RetrofitKotlin
**Description:** Advanced cryptocurrency tracker using Retrofit with RxJava3 for reactive programming.

**Key Features:**
- Real-time crypto price fetching from CoinMarketCap API
- RxJava3 for asynchronous operations
- CompositeDisposable for subscription management
- RecyclerView with crypto name, symbol, and USD price

**Tech Stack:** Kotlin, Retrofit, RxJava3, CompositeDisposable, RecyclerView, API integration

**Learning Focus:** Reactive programming with RxJava3, advanced Retrofit usage, subscription lifecycle management

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/RetrofitKotlin)

---

### CryptoWalletApp
**Description:** Cryptocurrency price tracker using live API data.

**Key Features:**
- Real-time crypto price fetching
- Retrofit + Coroutines for networking
- RecyclerView with custom adapter
- JSON parsing

**Tech Stack:** Kotlin, Retrofit, Coroutines, RecyclerView, API integration

**Learning Focus:** Network calls with Retrofit, Coroutines for async operations

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/CryptoWalletApp/CoroutineRetrofit)

---

### CloneInstagram
**Description:** A simplified Instagram clone with authentication and post sharing.

**Key Features:**
- Firebase Authentication (Email/Password)
- Firestore for post storage
- Firebase Storage for images
- User feed with posts

**Tech Stack:** Kotlin, Firebase Auth, Firestore, Firebase Storage, RecyclerView

**Learning Focus:** Firebase ecosystem integration, cloud storage, authentication flows

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/CloneInstagram)

---

### ArtBookProject (v1 - Classic Approach)
**Description:** A travel art book application where users can save historical artifacts with images from their gallery.

**Key Features:**
- Gallery image selection with runtime permissions
- Save artifact name, artist, and year
- RecyclerView display in separate Activity
- Local SQLite database for persistence
- Multi-screen support

**Tech Stack:** Kotlin, SQLite, Activity-based architecture, RecyclerView, Runtime permissions

**Learning Focus:** SQLite database operations, runtime permissions, Activity lifecycle, multi-screen apps

**Note:** This project was later modernized as [ArtbookNavFragment](#artbooknavfragment) using Navigation Component and Room.

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/ArtBookProject)

---

### ArtbookNavFragment (v2 - Modern Approach)
**Description:** Modernized version of ArtBookProject using Navigation Component and Room database.

**Key Features:**
- Multi-fragment navigation with Navigation Component
- Room database instead of SQLite
- Safe Args for type-safe data passing
- Gallery image selection
- Persistent art storage

**Tech Stack:** Kotlin, Navigation Component, Room, Fragments, Safe Args, Runtime permissions

**Learning Focus:** Jetpack Navigation, Room database migration from SQLite, fragment transactions, modern Android architecture

**Evolution:** This is the modernized version of [ArtBookProject](#artbookproject), showcasing progression from Activity + SQLite to Fragments + Room.

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/ArtbookNavFragment)

---

### SimpleStopwatch
**Description:** A functional stopwatch application.

**Key Features:**
- Start/Stop/Reset functionality
- Chronometer widget usage
- Simple and clean UI

**Tech Stack:** Kotlin, Chronometer, View Binding

**Learning Focus:** Android Chronometer, UI component lifecycle

[📂 View Code](https://github.com/borayldrmm/Android-Practice-Projects/tree/main/simpleStopwatch)

---

## 📈 Learning Progression

These projects demonstrate progression through:
1. **Basic UI & Kotlin** → CatchTheKenny, SimpleStopwatch
2. **Database Integration (Classic)** → ArtBookProject (SQLite + Activity)
3. **Database Integration (Modern)** → ArtbookNavFragment (Room + Navigation), TravelBook, SuperheroBook, ShoppingList
4. **Networking & APIs (Basic)** → JokeApp, CryptoWalletApp (Coroutines)
5. **Networking & APIs (Advanced)** → RetrofitKotlin (RxJava3)
6. **Firebase Integration** → CloneInstagram
7. **Architecture Patterns** → ShoppingList (MVVM), ArtbookNavFragment (Navigation)

**Key Evolution:**
- ArtBookProject (v1) → ArtbookNavFragment (v2) showcases migration from legacy to modern Android development practices
- CryptoWalletApp (Coroutines) → RetrofitKotlin (RxJava3) demonstrates different async programming approaches

---

## 🎓 Course Information

These projects were built during **[Atıl Samancıoğlu]'s Android Mobile Application Development Course**.

---

## 🚀 Next Steps

For more advanced, production-ready applications showcasing Clean Architecture, Jetpack Compose, and modern Android development practices, check out:

- **[FoodieHub](https://github.com/borayldrmm/FoodieHub)** - Food delivery app with Clean Architecture
- **[BeautyDate](https://github.com/borayldrmm/BeautyDate)** - Beauty salon management system

---

## 📬 Contact

**Bora Yıldırım**  
[GitHub](https://github.com/borayldrmm) | [LinkedIn](https://linkedin.com/in/borayldrmm)

---

## 📄 License

These projects are for educational purposes.
