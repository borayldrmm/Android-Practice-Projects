# 🚀 Android Practice Projects

A collection of Android applications built during my learning journey, demonstrating various concepts, architectures, and technologies in Android development.

> **Note:** These projects were created as part of my Android learning process. For production-ready work, please see my featured projects: [FoodieHub](link) and [BeautyDate](link).

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
| [CryptoWalletApp](#cryptowalletapp) | Cryptocurrency price tracker | Retrofit, Coroutines, RecyclerView |
| [JokeApp](#jokeapp) | Random joke fetcher | Retrofit, JSON parsing, API integration |

### 📱 UI & Database Practice
| Project | Description | Tech Stack |
|---------|-------------|------------|
| [ShoppingList](#shoppinglist) | Shopping list with local storage | Room Database, MVVM, RecyclerView |
| [TravelBook](#travelbook) | Location saving app with maps | Google Maps API, Room, SQLite |
| [SuperheroBook](#superherobook) | Superhero database browser | Room, RecyclerView, CRUD operations |
| [ArtbookNavFragment](#artbooknavfragment) | Art gallery with navigation | Navigation Component, Fragments, Room |

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

[📂 View Code](./01-CatchTheKenny) | [📸 Screenshots](./01-CatchTheKenny/screenshots)

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

[📂 View Code](./02-TravelBook) | [📸 Screenshots](./02-TravelBook/screenshots)

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

[📂 View Code](./03-SuperheroBook) | [📸 Screenshots](./03-SuperheroBook/screenshots)

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

[📂 View Code](./04-ShoppingList) | [📸 Screenshots](./04-ShoppingList/screenshots)

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

[📂 View Code](./05-JokeApp) | [📸 Screenshots](./05-JokeApp/screenshots)

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

[📂 View Code](./06-CryptoWalletApp) | [📸 Screenshots](./06-CryptoWalletApp/screenshots)

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

[📂 View Code](./07-CloneInstagram) | [📸 Screenshots](./07-CloneInstagram/screenshots)

---

### ArtbookNavFragment
**Description:** Art gallery app demonstrating Navigation Component usage.

**Key Features:**
- Multi-fragment navigation
- Room database for art storage
- Navigation Component
- Safe Args for data passing

**Tech Stack:** Kotlin, Navigation Component, Fragments, Room, Safe Args

**Learning Focus:** Jetpack Navigation, fragment transactions, data passing between screens

[📂 View Code](./08-ArtbookNavFragment) | [📸 Screenshots](./08-ArtbookNavFragment/screenshots)

---

### SimpleStopwatch
**Description:** A functional stopwatch application.

**Key Features:**
- Start/Stop/Reset functionality
- Chronometer widget usage
- Simple and clean UI

**Tech Stack:** Kotlin, Chronometer, View Binding

**Learning Focus:** Android Chronometer, UI component lifecycle

[📂 View Code](./09-SimpleStopwatch) | [📸 Screenshots](./09-SimpleStopwatch/screenshots)

---

## 📈 Learning Progression

These projects demonstrate progression through:
1. **Basic UI & Kotlin** → CatchTheKenny, SimpleStopwatch
2. **Database Integration** → TravelBook, SuperheroBook, ShoppingList
3. **Networking & APIs** → JokeApp, CryptoWalletApp
4. **Firebase Integration** → CloneInstagram
5. **Architecture Patterns** → ShoppingList (MVVM), ArtbookNavFragment (Navigation)

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
