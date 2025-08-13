# ISO20022-XML-Data-Conversion

This repository aims to explore Python code for parsing, extracting, and structuring data from **SWIFT ISO 20022** XML financial transaction messages. 

Using Python’s built-in **xml.etree.ElementTree** library, the script is able to navigate XML message structures with namespace awareness, ensuring accurate element targeting across both header and transaction data sections. The pandas library is then used to convert the extracted information into a DataFrame, enabling powerful filtering, aggregation, and export capabilities. The code captures key details such as sender and receiver BICs, message identifiers, timestamps, settlement methods, agent BICs, transaction IDs, amounts, currencies, and settlement dates. 

The transformation of unstructured XML into structured tabular data opens up a wide range of applications including financial transaction monitoring, compliance and AML screening, operational analytics, regulatory reporting, and even data warehousing for historical trend analysis or machine learning. By enabling structured access to the rich data contained in ISO 20022 messages, this project provides a foundational toolkit for building advanced financial analytics, real-time monitoring dashboards, and integration pipelines into larger payment processing systems.









Ask ChatGPT
