# Subtitle Manager

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/downloads/)
[![License](https://img.shields.io/github/license/Avielzi/subtitle-manager?style=for-the-badge)](LICENSE)

## 📚 Table of Contents

*   [English](#english)
    *   [Project Overview](#project-overview)
    *   [Features](#features)
    *   [Installation](#installation)
    *   [Usage](#usage)
    *   [Dependencies](#dependencies)
    *   [Contributing](#contributing)
    *   [License](#license)
*   [עברית](#hebrew)
    *   [סקירת פרויקט](#סקירת-פרויקט)
    *   [תכונות](#תכונות)
    *   [התקנה](#התקנה)
    *   [שימוש](#שימוש)
    *   [תלויות](#תלויות)
    *   [תרומה לפרויקט](#תרומה-לפרויקט)
    *   [רישיון](#רישיון)

---

<a name="english"></a>

## 🇬🇧 English

### Project Overview

The **Subtitle Manager** is a robust Python-based tool designed to streamline the process of managing subtitles for various media files. It provides a comprehensive solution for checking system compatibility, installing necessary dependencies, launching the main application, and performing clean uninstallation of its components. This project aims to offer a user-friendly experience through an interactive command-line interface, ensuring that users can easily maintain their subtitle environment.

### Features

*   **Python Version Compatibility**: Automatically verifies that the installed Python version meets the minimum requirement of 3.8+.
*   **Automated Dependency Management**: Installs and tracks essential Python packages such as `subliminal` and `babelfish`, ensuring a functional environment.
*   **Tkinter GUI Check**: Confirms the availability of Tkinter, which is crucial for the graphical user interface of the Subtitle Manager.
*   **Interactive Command-Line Interface**: Offers an intuitive menu-driven system for easy interaction, allowing users to perform various operations with simple inputs.
*   **Clean Uninstallation**: Provides a dedicated uninstallation process that removes only the packages installed by this setup script, preventing conflicts with other user-installed software.
*   **Application Launch**: Facilitates the direct launch of the main GUI application after ensuring all dependencies are met.

### Installation

To get started with the Subtitle Manager, follow these simple steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Avielzi/subtitle-manager.git
    cd subtitle-manager
    ```

2.  **Run the setup script**:
    Execute the setup script to check your environment and install all required dependencies. This command will automatically handle package installations.
    ```bash
    python subtitle_manager_setup.py install
    ```

### Usage

The `subtitle_manager_setup.py` script is the central point for interacting with the Subtitle Manager. It supports several commands:

*   **Interactive Menu (Default)**:
    Running the script without any arguments will launch an interactive menu, providing options to check status, install, run, or uninstall.
    ```bash
    python subtitle_manager_setup.py
    ```

*   **Install Dependencies**:
    Installs all necessary Python packages required by the application.
    ```bash
    python subtitle_manager_setup.py install
    ```

*   **Run Application**:
    This command first ensures all dependencies are installed (if not already present) and then launches the main GUI application (`subtitle_manager_gui_single_file_v_1_python.py`).
    ```bash
    python subtitle_manager_setup.py run
    ```

*   **Uninstall Packages**:
    Removes only the Python packages that were installed by this setup script, ensuring a clean removal.
    ```bash
    python subtitle_manager_setup.py uninstall
    ```

*   **Check Status**:
    Performs a comprehensive system check, verifying the Python version, pip installation, Tkinter availability, and the presence of all required packages.
    ```bash
    python subtitle_manager_setup.py check
    ```

### Dependencies

The `subtitle_manager_setup.py` script manages the following core Python packages:

*   `subliminal`
*   `babelfish`

Additionally, the project relies on `tkinter` for its graphical user interface. While `tkinter` is typically bundled with Python installations, some Linux distributions might require a separate installation (e.g., `sudo apt install python3-tk`).

### Contributing

Contributions to the Subtitle Manager project are highly encouraged! Whether it's bug reports, feature requests, or code contributions, your input is valuable. Please feel free to open issues or submit pull requests on the [GitHub repository](https://github.com/Avielzi/subtitle-manager).

### License

This project is released under the [MIT License](LICENSE). For more details, please refer to the `LICENSE` file in the repository.

---

<a name="hebrew"></a>

## 🇮🇱 עברית

### סקירת פרויקט

**מנהל הכתוביות** הוא כלי חזק מבוסס פייתון שנועד לייעל את תהליך ניהול הכתוביות לקבצי מדיה שונים. הוא מספק פתרון מקיף לבדיקת תאימות מערכת, התקנת תלויות נדרשות, הפעלת היישום הראשי וביצוע הסרה נקייה של רכיביו. פרויקט זה שואף להציע חווית משתמש ידידותית באמצעות ממשק שורת פקודה אינטראקטיבי, המבטיח שמשתמשים יוכלו לתחזק בקלות את סביבת הכתוביות שלהם.

### תכונות

*   **בדיקת תאימות גרסת פייתון**: מאמת אוטומטית שגרסת הפייתון המותקנת עומדת בדרישת המינימום של 3.8 ומעלה.
*   **ניהול תלויות אוטומטי**: מתקין ועוקב אחר חבילות פייתון חיוניות כגון `subliminal` ו-`babelfish`, ומבטיח סביבת עבודה תקינה.
*   **בדיקת Tkinter GUI**: מאשר את זמינות Tkinter, החיוני לממשק המשתמש הגרפי של מנהל הכתוביות.
*   **ממשק שורת פקודה אינטראקטיבי**: מציע מערכת מונחית תפריטים אינטואיטיבית לאינטראקציה קלה, המאפשרת למשתמשים לבצע פעולות שונות באמצעות קלטים פשוטים.
*   **הסרה נקייה**: מספק תהליך הסרה ייעודי שמסיר רק את החבילות שהותקנו על ידי סקריפט ההתקנה הזה, ומונע התנגשויות עם תוכנות אחרות שהותקנו על ידי המשתמש.
*   **הפעלת יישום**: מאפשר הפעלה ישירה של יישום ה-GUI הראשי לאחר הבטחת עמידה בכל התלויות.

### התקנה

כדי להתחיל עם מנהל הכתוביות, בצע את השלבים הפשוטים הבאים:

1.  **שכפול המאגר**:
    ```bash
    git clone https://github.com/Avielzi/subtitle-manager.git
    cd subtitle-manager
    ```

2.  **הפעלת סקריפט ההתקנה**:
    הפעל את סקריפט ההתקנה כדי לבדוק את הסביבה שלך ולהתקין את כל התלויות הנדרשות. פקודה זו תטפל אוטומטית בהתקנות חבילות.
    ```bash
    python subtitle_manager_setup.py install
    ```

### שימוש

סקריפט `subtitle_manager_setup.py` הוא נקודת המרכז לאינטראקציה עם מנהל הכתוביות. הוא תומך במספר פקודות:

*   **תפריט אינטראקטיבי (ברירת מחדל)**:
    הפעלת הסקריפט ללא ארגומנטים תפעיל תפריט אינטראקטיבי, המספק אפשרויות לבדיקת סטטוס, התקנה, הפעלה או הסרה.
    ```bash
    python subtitle_manager_setup.py
    ```

*   **התקנת תלויות**:
    מתקין את כל חבילות הפייתון הנחוצות הנדרשות על ידי היישום.
    ```bash
    python subtitle_manager_setup.py install
    ```

*   **הפעלת יישום**:
    פקודה זו מבטיחה תחילה שכל התלויות מותקנות (אם אינן קיימות כבר) ולאחר מכן מפעילה את יישום ה-GUI הראשי (`subtitle_manager_gui_single_file_v_1_python.py`).
    ```bash
    python subtitle_manager_setup.py run
    ```

*   **הסרת חבילות**:
    מסיר רק את חבילות הפייתון שהותקנו על ידי סקריפט ההתקנה הזה, ומבטיח הסרה נקייה.
    ```bash
    python subtitle_manager_setup.py uninstall
    ```

*   **בדיקת סטטוס**:
    מבצע בדיקת מערכת מקיפה, המאמתת את גרסת הפייתון, התקנת pip, זמינות Tkinter, ונוכחות כל החבילות הנדרשות.
    ```bash
    python subtitle_manager_setup.py check
    ```

### תלויות

סקריפט `subtitle_manager_setup.py` מנהל את חבילות הפייתון הליבתיות הבאות:

*   `subliminal`
*   `babelfish`

בנוסף, הפרויקט מסתמך על `tkinter` עבור ממשק המשתמש הגרפי שלו. בעוד ש-`tkinter` בדרך כלל נכלל בהתקנות פייתון, ייתכן שחלק מהפצות לינוקס ידרשו התקנה נפרדת (לדוגמה, `sudo apt install python3-tk`).

### תרומה לפרויקט

תרומות לפרויקט מנהל הכתוביות מעודדות מאוד! בין אם מדובר בדיווחי באגים, בקשות לתכונות או תרומות קוד, הקלט שלך חשוב. אל תהססו לפתוח בעיות או להגיש בקשות משיכה ב[מאגר GitHub](https://github.com/Avielzi/subtitle-manager).

### רישיון

פרויקט זה מופץ תחת [רישיון MIT](LICENSE). לפרטים נוספים, עיין בקובץ `LICENSE` במאגר.
