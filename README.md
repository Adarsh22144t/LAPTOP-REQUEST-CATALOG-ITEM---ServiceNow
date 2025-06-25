# 💻 Laptop Request Catalog Item (ServiceNow)

## 📌 Problem Statement

Employees in the organization need a **quick and efficient way to request laptops for work**. The current manual process is **prone to delays**, with no **dynamic form behavior** to guide users or ensure accurate data collection.

To solve this, a **ServiceNow Catalog Item** has been developed that includes:
- ✅ Dynamic fields
- 🔄 Form reset functionality
- 📋 Clear instructions for users
- 🔍 Full change tracking for governance and deployment

---

## 🚀 Features

- 🛠️ **Service Catalog Item** with user-friendly form to request laptops
- 🔀 **Dynamic field behavior** using Catalog UI Policies
- 🔁 **Reset form** functionality via UI Action
- 📦 **Exportable update set** for migration to other instances
- ✅ **Tested** on a different instance to ensure deployment integrity

---

## 🧾 Setup Steps

### 📍 Step 1: Create Local Update Set
Create a new local update set in ServiceNow to track all your changes.

### 💼 Step 2: Create Service Catalog Item
Create a catalog item named `Laptop Request` and add required variables such as:
- Laptop type
- Justification
- Duration needed

> 📸 **Screenshot 1**: *Laptop Request form in ServiceNow UI*

### 🔄 Step 3: Add Catalog UI Policies
Create UI policies to:
- Show/hide fields based on selections
- Make fields mandatory dynamically

> 📸 **Screenshot 2**: *Dynamic behavior of fields*

### ⚙️ Step 4: Create UI Action (Reset Form)
Add a `Reset Form` button using a client-side UI Action to clear the form inputs.

> 📸 **Screenshot 3**: *Reset Form button demonstration*

### ⏫ Step 5: Export Changes
Export the update set to an XML file for reuse in other ServiceNow instances.

### 🌐 Step 6: Import to Another Instance
Log in to a different ServiceNow instance and retrieve the update set.

### ✅ Step 7: Test the Catalog Item
Submit a test request and verify:
- Workflow triggers
- Form behavior
- Request visibility in ServiceNow portal

> 📸 **Screenshot 4**: *Submitted request overview*

---

## ✅ Conclusion

The **Laptop Request Catalog Item** project streamlines the laptop request process in the organization. By leveraging **ServiceNow’s powerful Service Catalog capabilities**, this solution:
- Enhances efficiency and reduces errors
- Replaces outdated manual processes
- Improves employee satisfaction with a modern interface

---

## 📂 Folder Structure

