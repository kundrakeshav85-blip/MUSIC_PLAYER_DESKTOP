# 🎵 C++ Music Player

A desktop-based Music Player developed using **C++ and SFML** with a modular Object-Oriented Programming (OOP) architecture.

The application provides essential music playback features along with playlist management and a simple graphical user interface.

## ✨ Features

- ▶️ Play / Pause music
- ⏹️ Stop playback
- ⏭️ Next song
- ⏮️ Previous song
- 🔊 Volume control
- ⏩ Seek through songs using the progress bar
- 🔀 Shuffle mode
- 🔁 Repeat mode
- 🎵 Automatic next-song playback
- ➕ Add MP3/OGG songs
- ➖ Remove songs from playlist
- 💾 Save playlist
- 📂 Load saved playlist
- 📜 Scrollable playlist
- 📊 Animated music visualizer
- ⌨️ Keyboard shortcuts

## 🛠️ Technologies Used

- **C++**
- **SFML 3**
  - SFML Graphics
  - SFML Audio
  - SFML Window
- **C++17 Filesystem**
- **Windows API** for file selection
- **Object-Oriented Programming**

## 🏗️ Project Architecture

The project is divided into multiple classes to keep the code modular and maintainable.

```text
MusicPlayer/
│
├── main.cpp
│
├── Song.h
├── Song.cpp
│
├── Playlist.h
├── Playlist.cpp
│
├── MusicPlayer.h
├── MusicPlayer.cpp
│
├── PlayerUI.h
├── PlayerUI.cpp
│
├── FileManager.h
├── FileManager.cpp
│
├── songs/
│
└── README.md
