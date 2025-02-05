# VebHolic_Ownership_Research
It is a research of ownership details and its source of generator and project name which have the unique queue id.

The dataset contains key columns like Project Name, Type, Capacity, Status, Location, Transmission Owner, and Queue ID. The Owner and Source columns are currently empty.

To populate the Owner and Source columns, I will:

1. Use the Transmission Owner column as an initial reference.
2. Use the Queue ID to infer ownership based on interconnection studies.
3. Assume ownership based on naming conventions and project details where possible.
4. Fill the Source column with the methodology used (e.g., "Transmission Owner Match," "Queue ID Reference," etc.).

To determine the ownership of generator projects using their Queue IDs, we can follow these steps:

1. Identify the Relevant Transmission Operator (ISO/RTO):
*Based on the project's location and transmission owner, determine the associated Independent System Operator (ISO) or Regional Transmission Organization (RTO).

2. Access the ISO/RTO Interconnection Queue:
*Visit the official website of the identified ISO/RTO.
*Navigate to their generator interconnection queue or project listings.

3. Search for the Project Using the Queue ID:
*Locate the search function within the interconnection queue page.
*Enter the project's Queue ID to find specific details.

4. Extract Ownership Information:
*Review the project details to identify the listed owner or interconnection customer.
*If direct ownership information isn't available, examine associated documents such as interconnection agreements or study reports, which may mention the project developer or owner.
