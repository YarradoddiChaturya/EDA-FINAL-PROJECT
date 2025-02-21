## For the final project, we are utilizing two datasets: Recall and Inspection. Our approach begins with data cleaning and preprocessing for both datasets. Following this, we will perform Exploratory Data Analysis (EDA) on each dataset individually to gain insights and address the respective hypothesis questions. Finally, we will analyze the hypothesis questions for the combined dataset to uncover relationships and trends across the two datasets.

## About The Dataset

## DataSet Link
https://datadashboard.fda.gov/ora/cd/recalls.htm

## Recal Dataset

A recall is a process initiated by a manufacturer, distributor, or regulatory authority (such as the FDA) to remove a product from the market due to concerns about its safety, effectiveness, or regulatory compliance. Recalls typically occur when a product poses a risk to public health or fails to meet quality or labeling standards

Columns: 17

Rows: 93834

FEI Number: A unique identifier for the recalling firm.

Recalling Firm Name: Name of the company recalling the product.

Product Type: The category of the product

Product Classification: Indicates the risk class of the product

Status: Current status of the recall

Distribution Pattern: Description of the geographic distribution of the product.

Recalling Firm City and State: Location details of the recalling firm.

Center Classification Date: The date the product was classified for recall.

Reason for Recall: The issue or defect that prompted the recall.

Product Description: A detailed description of the recalled product.

Event ID: A unique identifier for the recall event.

Event Classification: Classification of the recall event based on severity

Product ID: Unique identifier for the product involved.

Center: Regulatory center overseeing the recall

Recall Details: A URL linking to additional information about the recall

## Inspection Dataset

An inspection is a systematic process conducted by regulatory authorities or organizations to assess whether facilities, products, or operations comply with established laws, regulations, and standards. Inspections aim to ensure public health, safety, and quality across various industries, including food, healthcare, pharmaceuticals, and manufacturing.

Columns: 15

Rows: 304294

FEI Number: A unique identifier for the inspected entity or facility.

Legal Name: The official name of the inspected organization or company.

City, State, and Zip: Location details of the facility.

Country/Area: Geographic region of the facility.

Fiscal Year: The year in which the inspection was conducted.

Inspection ID: A unique identifier for the specific inspection event.

Posted Citations: Indicates whether citations (violations) were posted as a result of the inspection.

Inspection End Date: The date the inspection concluded.

Classification: Voluntary Action Indicated (VAI): Minor issues requiring corrective actions. No Action Indicated (NAI): The facility met all standards, no issues found.

Project Area: Focus area of the inspection, such as: Foodborne biological hazards (food safety issues). Monitoring of veterinary products (animal health and drug safety).

Product Type: The category of products involved, such as food, cosmetics, biologics, or veterinary items.

Additional Details: Extra notes or classifications related to the inspection. FMD-145 Date: Likely related to follow-up or compliance activities (often blank or specific).
