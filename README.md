# week-3
# 📞 Contact Management System

A simple and efficient **Python-based Contact Management System** that allows users to store, search, update, delete, and export contact information. The system uses dictionaries for data management and stores contacts permanently in a JSON file.

---

## 🚀 Features

* ✅ Add New Contact
* 🔍 Search Contact
* ✏️ Update Existing Contact
* 🗑️ Delete Contact
* 📋 View All Contacts
* 📂 Export Contacts to CSV
* 📊 View Contact Statistics
* 💾 Automatic Data Saving using JSON
* 📅 Track Recently Updated Contacts
* ✔️ Phone Number Validation
* ✔️ Email Validation

---

## 📁 Files Used

| File                  | Description                            |
| --------------------- | -------------------------------------- |
| `main.py`             | Main Python program                    |
| `contacts_data.json`  | Stores contact information permanently |
| `contacts_export.csv` | Exported contacts file                 |

---

## 🛠 Technologies Used

* Python 3
* JSON
* CSV
* Regular Expressions (re)
* Datetime Module

---

## 📌 Main Menu

```
==============================
          MAIN MENU
==============================
1. Add New Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. View All Contacts
6. Export to CSV
7. View Statistics
8. Exit
==============================
```

---

## 📷 Sample Execution

### Adding Contacts

```
--- ADD NEW CONTACT ---
Enter contact name: karthik
Enter phone number: 9493214456
Enter email (optional, press Enter to skip): karthik@gmail.com
Enter address (optional): to your left
Enter group (Friends/Work/Family/Other): family

✅ Contact 'karthik' added successfully!
✅ Contacts saved to contacts_data.json
```

---

### Viewing All Contacts

```
--- ALL CONTACTS (3 total) ---

👤 karthik
📞 9493214456
📧 karthik@gmail.com
👥 family

👤 sachitha
📞 8423326685
📧 sachitha@gmail.com
👥 family

👤 srikar
📞 6549146675
📧 srikar@gmail.com
👥 friends
```

---

### Updating Contact

```
Enter contact name to update: srikar

Leave blank to keep existing values.

Phone [6549146675]:
Email [srikar@gmail.com]:
Address [go stright]:
Group [friends]: family

✅ Contact updated successfully!
```

---

### Contact Statistics

```
--- CONTACT STATISTICS ---

Total Contacts: 3

Contacts by Group:
family : 2 contact(s)
friends : 1 contact(s)

Recently Updated (last 7 days): 3
```

---

### Export Contacts

```
Enter your choice (1-8): 6

✅ Contacts exported to contacts_export.csv
```

---

## 📊 Example Stored Contacts

| Name     | Phone      | Email                                           | Group   |
| -------- | ---------- | ----------------------------------------------- | ------- |
| karthik  | 9493214456 | [karthik@gmail.com](mailto:karthik@gmail.com)   | family  |
| sachitha | 8423326685 | [sachitha@gmail.com](mailto:sachitha@gmail.com) | family  |
| srikar   | 6549146675 | [srikar@gmail.com](mailto:srikar@gmail.com)     | family  |
| sanjana  | 9034571149 | [sanjana@gmail.com](mailto:sanjana@gmail.com)   | friends |

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project folder:

```bash
cd Contact-Management-System
```

3. Run the program:

```bash
python main.py
```

---

## Future Enhancements

* Password Protection
* Import Contacts from CSV
* GUI using Tkinter
* Contact Sorting
* Favorite Contacts
* Backup and Restore
* Search by Phone Number
* Search by Group
* SQLite Database Integration

---

## Author

**Karthik Chandra**

Python Mini Project

---

## License

This project is open-source and available for educational purposes.

