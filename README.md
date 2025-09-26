# Forensic-Examination-Project--Case-Study-Mickins

## 1.0. Part 1 

In this section, as a Forensic Investigator and Associate of Vericom Forensics, we would assess Mickins Construction Company's IT security environment, provide the best digital forensics and investigative services, and produce a technical report with detailed instructions that would assist law enforcement prosecutors in the event of a computerized incident. In addition, a case study outlines the entire process, from gathering evidence to presenting findings in court. 

 

## 1.1. Introduction 

The Mickins Construction Company was founded by Calos Coms in the UK and established in 2013. Mickins Construction Company is a British engineering company that specializes in bridge construction. The firm is responsible for some of the significant bridge constructions in the UK, including Millennium Bridge, and it specializes in supplying bridges to more than 110 countries. The UK’s Export Credit Guarantee Department (ECGD) frequently underwrites the company's contracts with foreign governments. 

 

## 1.2. Purpose of the Report 

This report aims to assist Mickins Construction Company in preparing for a productive digital forensic investigation. The report analyses critical elements of fraudulent behavior, utilizes the gathered information for the study, and presents findings to the court. Furthermore, it emphasizes the importance of adhering to accreditation standards and maintaining the necessary integrity for legal proceedings. 

## 1.3. IT Security Management Policy at Mickins 

Due to its involvement in data at Mickins construction company in the UK, handling essential data and regulations is very important. Information governance frameworks include the integrity, confidentiality, and availability of data. Mickins Construction uses ISO 27001, an anal standard framework for most businesses and IT organizations. To protect this information, more and more companies are becoming ISO 27001 certified in processing personal data and related matters in compliance with the Cybersecurity Framework UK, which the GDPR strongly influenced. 

The UK organization's IT Security Management Policy typically comprises several vital components. These policies must align with international standards like ISO/IEC 27001, a globally recognized standard offering ISMS Framework. An ISMS framework provides a structure for managing information security. The ISMS standard offers a methodical framework for ensuring the continued safety of critical enterprise data. 

Mickins Construction company has also improved and advanced technology to protect the data from cyber-attacks by investing in a well-trained and experienced workforce—training and retraining are vital to mitigating cybersecurity risks (IT GOVERNANCE, 2018). 

The following information details the complete investigation procedure for digital evidence at Vericom Forensics UK organization. It encompasses the assigned tasks, their importance, and the steps required to accomplish them (E - council, 2023). 



 ### 1.3 Digital Forensic Investigator's Responsibility

| Responsibility | Why it is Important | How to Accomplish it |
|---|---|---|
| **First Step – Presenting and handling digital evidence** | Preserving the integrity of evidence is vital to avoid contamination or compromise. | Develop a professional manual outlining methods and tools for digital forensic investigations. |
| **Second Step – Search and Seizure** | Devices involved in the crime must be secured to prevent tampering. | Identify and carefully seize relevant devices for forensic examination. |
| **Third Step – Data Acquisition** | Gathering accurate data from the suspect’s assets is critical to the investigation. | Acquire all necessary information using forensic imaging techniques. |
| **Fourth Step – Evidence Assessment** | Proper scope ensures relevance of the collected evidence. | Relate evidential data to the incident and determine its value to the case. |
| **Fifth Step – Evidence Collection & Analysis** | Standardized methods guarantee reliable and admissible results. | Use forensic tools to extract, preserve, and analyze information from seized devices. |
| **Sixth Step – Staying Updated** | Forensics evolves rapidly; investigators must stay current. | Attend workshops, training, and conferences; pursue continuous professional development. |
| **Seventh Step – Documentation & Reporting** | Courts require well-documented, verifiable evidence. | Record findings with detailed notes, screenshots, and structured reports. |
| **Eighth Step – Maintaining Integrity** | Investigators must remain unbiased and impartial. | Uphold confidentiality, ethics, and professionalism throughout the case. |
| **Ninth Step – Cross-Checking** | Accuracy and reliability strengthen the case. | Review findings thoroughly and seek peer/supervisor validation. |
| **Tenth Step – Expert Testimony** | Expert witnesses validate the accuracy of the evidence. | Engage qualified experts to interpret findings during legal proceedings. |
| **Final Step – Court Presentation** | Clear presentation ensures correct legal outcomes. | Prepare detailed reports and evidence ahead of court submission. |

> This structured framework demonstrates my **hands-on knowledge and practical experience** as a Digital Forensic Investigator, highlighting my ability to conduct end-to-end forensic investigations in line with professional and legal standards.


Conclusion 

Knowing the Value of Digital Evidence is vital to organizations. An In-depth Guide to Appropriate Evidence Handling in Mickins will hasten the investigation. The primary objective of this document is to underscore the crucial value of digital evidence and shed light on the prevalent oversight observed in numerous organizations. Often, available evidence proves inadequate or needs more appropriate handling protocols when it becomes necessary to establish the veracity of charges related to fraudulent transactions or malicious activities. By offering a comprehensive manual on proper evidence handling within Mickins Company, this paper aims to streamline the process of prosecuting attackers, ultimately facilitating law enforcement agencies in achieving favorable outcomes. 

1.4. A) Case Background 

Mickins construction firm manager John Prone has been tasked with managing the impending election among the 120 branches, including UK branches, to determine who would be the next chairman of the board of directors of Mickins construction company. The board of directors chose John for this critical position. The introduction of the Bimodal Voters Authentication System (BVAS), a computerized voting method, was advocated to improve transparency and efficiency. 

However, numerous stakeholders and electoral commissions expressed concerns about purported election-related violations, notably concerning the electronic transmission of election results. Because of the issues, the presumed winner filed a lawsuit against John, who oversaw the election's behavior.  

After a few court proceedings, access was granted to investigate the Bimodal Voters Authentication System (BVAS). There was clear evidence that the director manipulated and deleted the results of the presumed winner, and this was because he succumbed to being influenced by contesting oppositions by accepting bribes, compromising the integrity of the electoral process, and potentially jeopardizing the Mickins construction company's future. The election computer has been submitted to digital forensic examination to obtain evidence that can either incriminate or exonerate manager John Prone and his accomplices.

1.5. B) Tools and techniques used to commit and investigate the Cyber-Crimes 

The forensic tool used in investigating the suspect fraudulent act was Access Data Forensic Toolkit (FTK) Imager 4.7.1 Version. This FTK imager was used to create a disk image, conduct analysis, and recover files of the disk image from the suspect drive. A sound forensic practice is to acquire copies (prints) of the affected system’s data and operate on those copies to aid in this process. Further, the FTK tool calculates MD5 and SHA1 hash values and can verify that the integrity of the data image is consistent with the created forensic image. Access Data Forensic Toolkit is a standalone disk imaging software known as FTK Imager, one of the most admired software suites available to digital forensic professionals (Holt et al., 2022). 

1.6. c) Creating digital evidence forensics 

Some procedures and goals must be met for this investigation to successfully pursue the culprit. Based on this case study, the use of an external USB drive from the suspect, including a Virtual machine, to carry out this investigation. 
The methods and tools for creating, analyzing, and retrieving files from a disk image of the suspect drive are listed below (Chandel, 2020). 


### 1.6(c) Creating Digital Evidence Forensics

The following steps outline the process of creating digital forensic evidence using industry-standard tools. Each step includes space for screenshots that demonstrate the procedure.

---

#### Step 1 – Launch the Forensic Tool (FTK Imager)
Open **FTK Imager** to begin creating a forensic image of the suspect drive or device.

📌 *Screenshot Placeholder:*  
![Step 1 – FTK Imager Launch](/images/step1_ftk_launch.png)

---

#### Step 2 – Select Evidence Acquisition Option
Choose the option **"Create Disk Image"** from the File menu. This ensures a forensic bit-by-bit copy of the source media.

📌 *Screenshot Placeholder:*  
![Step 2 – Create Disk Image Option](/images/step2_create_image.png)

---

#### Step 3 – Choose Evidence Source
Select the source drive, removable media, or image file that you intend to investigate.

📌 *Screenshot Placeholder:*  
![Step 3 – Select Evidence Source](/images/step3_select_source.png)

---

#### Step 4 – Configure Image Destination and Format
Specify the output location for the forensic image and select the image type (e.g., **E01, Raw (dd)**).  
Include a descriptive case identifier (case number, examiner name, description).

📌 *Screenshot Placeholder:*  
![Step 4 – Configure Image Format](/images/step4_configure_format.png)

---

#### Step 5 – Add Case Metadata
Provide metadata such as:  
- Case number  
- Examiner name  
- Evidence description  

This helps maintain proper **chain of custody**.

📌 *Screenshot Placeholder:*  
![Step 5 – Add Case Metadata](/images/step5_case_metadata.png)

---

#### Step 6 – Verify with Hash Values
Select the option to generate **hash values (MD5/SHA1)** during acquisition.  
This guarantees integrity and ensures the image matches the original media.

📌 *Screenshot Placeholder:*  
![Step 6 – Hash Verification](/images/step6_hash_verification.png)

---

#### Step 7 – Begin Acquisition
Start the acquisition process. The forensic tool creates a **bit-by-bit copy** of the suspect media and stores it as a forensic image file.

📌 *Screenshot Placeholder:*  
![Step 7 – Acquisition Process](/images/step7_acquisition.png)

---

#### Step 8 – Validate the Image
Once acquisition completes, validate the forensic image by comparing its hash value with the original source hash.  
This confirms the evidence was preserved without alteration.

📌 *Screenshot Placeholder:*  
![Step 8 – Validate Forensic Image](/images/step8_validate.png)

---

#### Step 9 – Document the Process
Record details of the acquisition in the forensic report, including:  
- Tool used  
- Source and destination details  
- Date and time  
- Hash values  

📌 *Screenshot Placeholder:*  
![Step 9 – Documentation Example](/images/step9_documentation.png)

---

> These steps demonstrate my ability to **create, preserve, and validate digital evidence** in line with forensic standards, ensuring the evidence remains legally admissible.
