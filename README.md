# **Laptop Request Catalog Item – ServiceNow Project**

A streamlined and dynamic Service Catalog item built in ServiceNow to automate and simplify the laptop request process within an organization. This project replaces a slow, manual workflow with a guided and interactive form that ensures accurate data capture, faster approvals, and proper governance through tracked changes.

---

## 🚀 **Project Overview**

Employees often rely on laptops for daily operations, but traditional request processes are manual and error-prone, leading to delays. This project introduces a **Laptop Request Catalog Item** equipped with dynamic form fields, validation rules, reset functionality, and automated approval routing.

The system improves user experience while ensuring that IT teams receive complete and correct data before processing each request.

---

## ✅ **Key Features**

### **1. Dynamic Form Behavior**

* Fields appear or hide based on user selections
* Mandatory conditions controlled through **Catalog UI Policies**
* Real-time guidance using **Catalog Client Scripts**

### **2. User-Friendly Enhancements**

* Clear instructions for users
* Dedicated **Reset Form** feature
* Error validation for mandatory details

### **3. Workflow Integration**

* Automated approvals using **Flow Designer**
* Routing based on department or laptop type
* Notifications to requesters and approvers

### **4. Governance & Deployment**

* All changes tracked using **Sys_Audit**
* Update Sets used for controlled migration
* Audit trail maintained for form and workflow updates

---

## 🛠️ **Technical Components**

| Component                  | Purpose                                          |
| -------------------------- | ------------------------------------------------ |
| **Service Catalog Item**   | Core laptop request form                         |
| **Catalog UI Policies**    | Manages dynamic visibility & mandatory states    |
| **Catalog Client Scripts** | Handles real-time logic & reset functionality    |
| **Flow Designer**          | Approval workflow and email routing              |
| **Sys_Audit**              | Tracks form, workflow, and configuration changes |
| **Update Sets**            | Deployment and version tracking                  |

---

## 📘 **Development Phases**

1. Create the Laptop Request Catalog Item
2. Add basic fields (Laptop Type, Justification, Department, etc.)
3. Implement dynamic behavior using UI Policies
4. Add reset and guidance using Client Scripts
5. Configure approval routing in Flow Designer
6. Test request submission flow
7. Package and move changes via Update Sets
8. Document and validate governance logs

---

## 🧩 **Solution Architecture Diagram**

A simplified visual representation of the project architecture:

```
User → Laptop Request Catalog Item → UI Policies → Client Scripts → Flow Designer → Sys_Audit
```



---

## 🧪 **Testing Process**

* Validate dynamic visibility of fields
* Confirm reset button functionality
* Test approval routing by department
* Verify audit entries in **Sys_Audit**
* Check notifications sent to users and approvers

---

## ⚙️ **Prerequisites**

* ServiceNow Personal Developer Instance
* Access to Service Catalog configuration
* Ability to create/update Flow Designer flows
* Update Set permissions

---

## 📄 **Problem Statement (Summary)**

Employees need a quick and efficient way to request laptops for work. The existing process is manual, slow, and lacks dynamic guidance. This project implements a ServiceNow Catalog Item with dynamic fields, instructions, reset functionality, and proper governance to ensure accurate and efficient laptop requests.

---

## 🤝 **Contributing**

Contributions, suggestions, and improvements are welcome.
Feel free to create issues or submit pull requests.

---

## 📜 **License**

This project is released under the **MIT License** unless your institution prefers a different one.

---
