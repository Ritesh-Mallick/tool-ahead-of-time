# 🛠️ Custom Modifications in TAOT Library Fork

This repository contains custom modifications to the **TAOT library**.

---

## 🔄 **Key Modifications**

### **Removed Tool Result Formatting Function**
- Previously, the library included a function **format_tool_result** in **agent.py** in src folder that **manually formatted tool results** into Natural Language Responses.
- This function has been **removed**, as tools can now directly return responses in the expected structured format using Pydantic Classes.

### **Example**
- Below is the output we got using tools.


