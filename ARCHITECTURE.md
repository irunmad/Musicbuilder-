# MusicBuilder Architecture

## Главная идея

MusicBuilder не является DAW.

MusicBuilder — это AI-библиотека музыкальных элементов с простым редактором проектов.

---

# Workflow

Upload Song

↓

Analyze

↓

Create Library Objects

↓

Build Project

↓

Export MP3

---

# Library

Библиотека содержит только исходные элементы.

Исходные элементы никогда не изменяются.

Каждый элемент имеет уникальный ID.

---

# Project

Проект хранит ссылки на элементы библиотеки.

Проект не изменяет оригиналы.

Каждый элемент проекта можно:

- Move
- Trim
- Stretch
- Pitch
- Mute
- Delete

---

# Analysis

Stage 1

- Detect Artist
- Detect Title
- Detect BPM
- Detect Key

Stage 2

- Stem Separation

Stage 3

- Slice Detection

Stage 4

- Advanced Analysis (future)

---

# Export

Export MP3

Export WAV

Export Project (future)
