# NguyenNhat API Usage Guide

This guide explains how to integrate and use the **NguyenNhat API** in your Visual Studio project to interact with **Roblox**.

---

## 📦 Prerequisites

- A properly set up Visual Studio project.
- The NguyenNhat API library (`QuorumAPI.dll` file).

---

## ⚙️ Setup Instructions

### 1. Prepare the Project and Files

- **Switch to x64 Build**:
  - Go to **Build** → **Configuration Manager**.
  - Under **Active solution platform**, select `x64`. If not available, click **New...** and create `x64`.

- **Extract Files**:
  - From the NguyenNhat API archive, extract:
    - `QuorumAPI.dll`
    - `bin` folder

- **Place Files**:
  - Move both the `QuorumAPI.dll` and the `bin` folder into your project’s output directory:
    - `YourProject/bin/x64/Debug/`
    - or `YourProject/bin/x64/Release/`

---

### 2. Add the API as a Reference

- In **Solution Explorer**, right-click **References**.
- Click **Add Reference...**.
- Browse to the location of `QuorumAPI.dll`.
- Select and click **Add**.

---

### 3. Import the Namespace

At the top of your C# file, add:

```csharp
using QuorumAPI;
