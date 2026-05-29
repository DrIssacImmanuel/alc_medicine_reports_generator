# ALC Medicine Reports Generator

A tool/application designed to easily generate ALC-related documents in ECHS Polyclinics.

## Installation

1. Download and install the attached **ALC Medicine Reports Generator** application.
2. **Note on Windows Permissions:** If prompted by Windows Defender, click on **"More Info"** and then **"Run Anyway"**. 
   *(Note: You might need to temporarily turn off 'Smart App Control' in Windows Defender settings if the application is blocked).*

---

## How to Use It

### Step 1: Prepare Your Folders
It is highly recommended to create a main folder for the current day, containing two sub-folders inside it:
* One folder to hold your raw data files.
* One folder to serve as the destination for your generated reports.

### Step 2: Prepare the Data Sheets
Right-click and create two Microsoft Excel files within your data folder:

#### 1. ALC Report
This file should contain the daily reports of ALC Medicines ordered. Data can be captured from the approval page in the **OIC Module**, or from the receive order page post-approval in the **Stock Manager Module**.

**ALC Medicines Ordered Sheet Example:**
| # | Nomenclature | Patient Name | Qty |
| :--- | :--- | :--- | :--- |
| 1 | Medicine 1 | Name 1 | 30 |
| 2 | Medicine 2 | Name 1 | 60 |
| ... | So on... | | |

#### 2. Patient Data Sheet
This file should contain the Patient Data for that day. Data can be captured from the **OIC Module** (Daily Patient Report).

**Patient Data Sheet Example:**
| # | Patient Name | ESM Name | Service No | Rank | DOB | Relation with ESM | Mobile No | Card No | Card Type | OPD Remark |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Name | Name | Rk No | DOB | Rel | XX | XX | XX | | |
| 2 | Name | Name | Rk No | DOB | Rel | XX | XX | XX | | |
| ... | So on... | | | | | | | | | |

---

### Step 3: Run the Generator
1. Open the **ALC Medicine Reports Generator** by double-clicking it (or right-click and select Open).
2. **Select the ALC data** for the day.
3. **Select the Patient data** for the day.
4. **Specify the destination folder** (the folder you created to store the generated reports).
5. Click **Generate Reports**.

---

## Generated Outputs
Once processing is complete, open your destination folder. The application automatically generates and saves three custom reports:
1. **Patient Name-wise ALC order list**
2. **Consolidated list of medicines ordered** for that day
3. **Merged order list** including the patient's complete full details

[Download the pdf file here](README.pdf)
