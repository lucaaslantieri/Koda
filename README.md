# Koda
Koda is a high-performance personal archiving system designed to centralize daily reflections with automated cultural logging. By integrating external APIs, Koda automatically fetches metadata for movies and music, allowing the user to focus on the narrative of their own life. It blends minimalist UI design with a robust "Dev Mode" for real-time system diagnostics.

V1.0
* Dynamic Metadata Engine: Logic implemented to fetch and parse JSON data from the TMDB API, enabling automated retrieval of high-resolution posters and media metadata.
* Contextual Input Architecture: A polymorphic form system that reconfigures its UI components (TextFields, Pickers, and Labels) based on the Entry category.
* SwiftData Persistence Layer: Implementation of a localized Schema to manage Entry objects, supporting CRUD operations (Create, Read, Update, Delete) with persistent storage.
* Reactive UI & Global State: Utilization of @AppStorage and @StateObject to maintain global consistency for font sizing, language selection, and appearance modes.
* Shake-Triggered CLI: Integration of UIWindow motion detection to instantiate a hidden Developer Mode, featuring a custom-built Command Line Interface.
* System Diagnostics Console: A low-level terminal capable of executing network pings to verify API availability and reporting latency in milliseconds.
* Adaptive Layout System: Logic to toggle between LazyVGrid (Tile mode) and LazyVStack (List mode) based on user preference stored in persistent memory.
* Input Validation Framework: Conditional logic applied to the ToolbarItem to disable the save action unless the title and content fields pass non-empty string validation.
* Multimedia Integration: Support for PhotosUI to handle manual image selection and Data conversion for local storage within the SwiftData model.
* Localization & Region Detection: Automatic detection of Locale.current to initialize the application in either English or Spanish depending on the device's hardware settings.
* Haptic & Acoustic Feedback: Implementation of UINotificationFeedbackGenerator and AudioServices to provide sensory confirmation of successful data persistence.

For problems or anything, please send me an email to: lucaslantier24@gmail.com 
