# 🛠️ Custom Modifications in TAOT Library Fork

This repository contains custom modifications to the **TAOT library. The changes simplify tool result formatting while ensuring that responses conform to Pydantic models when applicable.

---

## 🔄 **Key Modifications**

### **Removed Tool Result Formatting Function**
- Previously, the library included a function that **manually formatted tool results** into Pydantic models.
- This function has been **removed**, as tools now directly return responses in the expected structured format.
