# 🎮 **RentaGame** 
*Game Renting and Purchasing Platform*

RentaGame is a comprehensive software engineering project designed to deliver a seamless platform for renting and purchasing video games. By addressing gaps in existing solutions, such as the lack of renting options and limited customer engagement, RentaGame aims to enhance the gaming experience for users worldwide.

---

## 🌟 **Key Features**

- **Game Renting and Purchasing**:
  - Rent games for a limited period and return them with ease.
  - Purchase games to add permanently to your library.
- **User Feedback and Reviews**:
  - Share opinions and ratings on games.
  - Engage with publishers and the gaming community.
- **Child Safety Features**:
  - Restricted access for younger users (<13 years old).
  - Content filtering for age-appropriate games.
- **Advanced Game Search**:
  - Search games by genre, language, number of players, and title.
  - Filters for newly added games and promotions.
- **Personalized User Library**:
  - Manage owned, rented, and wishlist games.
- **Patch Updates and DLC Support**:
  - Automatically download and install patches.
  - Purchase and integrate downloadable content (DLC).

---

## 📚 **Design Goals**

- **Efficiency**: Optimize system operations for real-time responses.
- **Usability**: Ensure intuitive navigation and smooth game-related transactions.
- **Security**: Protect user data and ensure safe financial transactions.
- **Fault Tolerance**: Backup data regularly and enable recovery in case of failures.
- **Compatibility**: Support various devices and operating systems.

---

## 🔧 **System Models**

### **1. Class Diagrams**
  - Define system structure, including classes for users, games, transactions, and publishers.
  - Highlight relationships such as inheritance, associations, and dependencies.

### **2. Sequence Diagrams**
  - Capture dynamic behaviors for scenarios like:
    - Searching games by filters.
    - Renting or purchasing games.
    - Adding reviews or comments.

### **3. Activity Diagrams**
  - Represent workflows for:
    - User login and authentication.
    - Game renting and purchasing.
    - Patch updates and user blocking activities.

### **4. Statechart Diagrams**
  - Show transitions for game states:
    - Available, rented, or purchased.
    - Pending updates or DLC installation.

---

## 🏗️ **Subsystem Decomposition**

### **Major Components:**
- **Authentication System**: Handle user registration, login, and account management.
- **Publisher System**: Enable publishers to add games, manage prices, and provide updates.
- **Game Management System**: Allow users to search, rent, buy, and review games.
- **Financial System**: Securely manage payments and transaction history.
- **Content Management System**: Deliver updates, DLCs, and promotional content.

---

## 💻 **Hardware/Software Mapping**

| Component            | Description                           |
|-----------------------|---------------------------------------|
| **Server**           | Centralized server for hosting the app. |
| **Client Devices**   | Desktop, mobile, or console access.   |
| **Software**         | Developed with UML principles using `.vp` files. |

---

## 📂 **Repository Structure**

```
RentaGame/
├── docs/                     # Design and documentation files
├── vp_files/                 # Visual Paradigm project files
├── diagrams/                 # UML diagrams (class, sequence, activity, statechart)
├── README.md                 # Project documentation
```

---

## 📊 **Example Scenarios**

1. **Search and Rent Games:**
   - User searches for a multiplayer action game in French.
   - Rents the game for a week, with reminders for return dates.

2. **Review and Rate Games:**
   - User rates a purchased game 4/5 stars.
   - Leaves a comment about its engaging gameplay.

3. **Access Patch Updates and DLCs:**
   - Automatically installs a patch for bug fixes.
   - Purchases a DLC for additional content.

---

## 🔄 **Advanced Features**

| Feature                | Description                                    |
|------------------------|------------------------------------------------|
| **Concurrency**        | Multiple users can comment on the same game.  |
| **Data Recovery**      | Automatic recovery from unexpected failures.  |
| **Performance**        | Optimized for high traffic and large libraries. |

---

## ✨ **Applications**

- **Game Enthusiasts**: Manage game libraries and discover new content.
- **Game Publishers**: Promote games, updates, and DLCs.
- **Parents**: Control game access for younger players.

---

## 🤝 **Contributions**

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

---
