---
name: Bug Report
about: Report a bug to help us improve the project.
title: "[Bug]: "
labels: ["bug", "triage"]
---

# Bug Report

Thank you for contributing to our project by reporting a bug! To help us understand and resolve the issue as quickly as possible, please provide the following details.

---

### **Basic Information**

* **Title**: (A concise, descriptive summary of the issue. e.g., `[Bug]: MiniMax-M1 fails to initialize MCP tools`)
    * *Please start your title with `[Bug]: `*

* **Models Used**: (Please select all applicable models from the list below. If "Other," please specify.)
    * [ ] MiniMax-M1
    * [ ] speech-02-hd
    * [ ] Other (Please specify):

* **Scenario Description**: (Briefly describe the context in which the bug occurred. e.g., "Attempting to integrate Minimax-M1 as an MCP tool results in an error.")

---

### **Problem Validation**

To help us narrow down the cause, please confirm the following by checking the boxes:

* [ ] I have thoroughly reviewed and followed the GitHub READMEs for `Minimax-MCP` and `Minimax-MCP-JS`.
* [ ] I have checked the official Minimax documentation and found no relevant solution.
* [ ] I have reviewed the relevant framework documentation (if applicable) and found no useful information.
* [ ] I have searched existing GitHub issues and confirmed that this bug has not been reported previously.

---

### **Environment Details**

Please provide comprehensive information about your development environment:

* **System Information**: (Include details such as your operating system, Python version, relevant software versions, and GPU information if applicable.)
    ```
    # Example:
    OS: Ubuntu 22.04 LTS
    Python: 3.9.18
    CUDA: 11.8
    GPU: NVIDIA A100
    ```

* **Python Packages (`pip list`)**: (Please paste the complete output of `pip list` here.)
    ```python
    Package             Version
    ------------------- -----------
    accelerate          0.33.0
    ...
    (Paste output of `pip list` here)
    ```

* **Trace-ID**: (If applicable, please copy and paste the trace-ID of the problematic request. e.g., `abcdef1234567890`)

---

### **Description of the Bug**

Please provide a detailed description of the bug, following the recommended structure below. Feel free to modify it as needed.

* **Steps to Reproduce**:
    Provide clear, numbered steps to reproduce the issue.
    1.  Go to '...'
    2.  Click on '....'
    3.  Scroll down to '....'
    4.  See error

* **Expected Behavior**:
    What did you expect to happen when performing the steps above?

* **Actual Behavior**:
    What actually happened, detailing the unexpected outcome?

* **Error Logs (if any)**:
    Please paste any relevant error messages or console output here.
    ```bash
    Error message or log output here.
    ```

* **Screenshots**:
    Please paste any screenshots of the error or unexpected behavior here. You can drag and drop images directly into this field when submitting the issue.
