# 📚 Time Table Generator

> A smart solution for the age-old challenge of academic scheduling, inspired by real-world timetabling headaches at educational institutions.

[![GitHub](https://img.shields.io/badge/GitHub-Yassine--64-blue?style=flat&logo=github)](https://github.com/Yassine-64)

## 🎯 Overview

Time Table Generator is an intelligent scheduling system that takes the complexity out of creating academic timetables. Born from the frustration of manual scheduling, this project uses sophisticated constraint satisfaction algorithms to automatically generate conflict-free schedules that work for everyone.

## 🧠 The Science Behind It

This system is built on the foundation of Constraint Satisfaction Problem (CSP) modeling, ensuring that every generated timetable is both practical and feasible.

### Core Components

- **Variables**: Available time-slots in the schedule
- **Domain**: Complete set of subjects requiring scheduling
- **Constraints**: Rules that ensure a logical and practical timetable

### Smart Constraints

- ⚡ Collision prevention between subjects
- 🔄 Automatic grouping of multi-hour lectures
- 👩‍🏫 Teacher availability optimization
- 🚫 Subject spacing requirements

## 📝 Input Configuration

### Course Details

- Course name and identifier
- Instructor information
- Weekly lecture frequency
- Lecture/lab duration
- Instructor availability windows

### Global Parameters

- Institutional working hours
- Active working days
- Subject separation rules

## 🛠️ Technology Stack

<img width="650px" src="https://user-images.githubusercontent.com/56782318/141955813-15e0340d-72a6-4a49-afd0-40513cba9673.png"/>

## 📸 Interface Preview
<img width="900px" src="https://user-images.githubusercontent.com/56782318/141957891-8aa7cd5f-62b9-4680-a312-59307e184a4f.png"/>
<img width="900px" src="https://user-images.githubusercontent.com/56782318/141958163-f2654097-9f44-4a5a-a311-3e48e77b168d.png"/>

## 🚀 Getting Started

### Prerequisites

- Node.js
- Python 3.x
- npm or yarn

### Installation Steps

1. Clone the repository

```bash
git clone https://github.com/Yassine-64/timetable-generator.git
```

2.Install dependencies

### Frontend dependencies

```bash
npm install
```

### Backend dependencies

```bash
cd backend
pip3 install -r requirements.txt
```

3.Run the application

```bash
npm start
```

4.Start the backend server

```bash
cd backend
python3 app.py
```

## 💡 Key Features

🎯 Intelligent conflict resolution
⚡ Real-time schedule generation
🔄 Flexible constraint configuration
👥 Multi-user support
📱 Responsive interface
