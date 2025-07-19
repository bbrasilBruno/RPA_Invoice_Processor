# RPA_Invoice_Processor

🤖 RPA – Intelligent Invoice Reading with AI Builder
⚠️ This project is an adapted representation of a real automation developed in a corporate environment. No sensitive data is included in this repository.

🧠 Overview
This project was developed to automate the reading of invoices (XML and PDF) received via email, using Power Automate in conjunction with AI Builder to interpret documents and generate a standardized XML file ready for input into SAP.

The entire logic—from training the AI model to composing the final XML—was implemented entirely within the Power Automate environment, with no external code.

🛠️ Technologies and Tools Used
Power Automate Desktop and Cloud

AI Builder (Form Processing)

Outlook Connector

SharePoint / OneDrive (file storage)

SAP (final input via XML file)

🔄 Automated Workflow
📥 Automatic email capture with XML or PDF attachments containing invoices.

🧠 Invoice layout interpretation using a trained model in AI Builder.

📊 Extraction of key fields:

Issuer’s CNPJ

Invoice total amount

Invoice number

Issue date

Access key

🔄 Validation of extracted information, including format and consistency rules.

🧾 Automated XML file creation, formatted according to SAP specifications.

📤 Storage in a shared folder and/or automatic submission to the SAP system.

📈 Achieved Results
Metric	Before Automation	After Automation
Avg. time per invoice	~8 minutes	< 1 minute
Daily volume processed	40–60 invoices	Up to 200/day
Manual errors	Frequent	Eliminated
Human involvement	Full	Only exceptions

🧩 Project Highlights
Advanced use of AI Builder with custom-trained models based on real invoice samples from the company.

Entire automation logic built within Power Automate, with no external scripting required.

Fully no-code/low-code architecture, enabling easy maintenance by business users.

Seamless integration with SAP through automatically formatted XML output.

