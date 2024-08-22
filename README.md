# Hotel Booking Demand Data Pipeline

This project is a data pipeline designed to process and analyze the [Hotel Booking Demand dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data). The pipeline is implemented using **Dataform GCP** and is connected to a GitHub repository for version control. The final output of the pipeline is a cleaned and enhanced dataset, which is then visualized using **Power BI**.

## Project Structure

The project consists of the following key components:

1. **Dataform GCP Pipeline**:
   - **Data Cleaning**: Various cleaning operations were applied to the dataset, such as handling missing values, correcting data types, and removing duplicates.
   - **Feature Engineering**: New columns were added to enhance the dataset, which included calculated fields based on existing data.
   - **Final Table Creation**: A final table was created, summarizing the cleaned and enhanced data, which is ready for further analysis and visualization.

2. **Version Control**:
   - The pipeline code is stored in a GitHub repository connected to Dataform GCP. This allows for easy tracking of changes, collaboration, and deployment.

3. **Visualization**:
   - The final table from the Dataform GCP pipeline is connected to **Power BI** for creating interactive visualizations that provide insights into the hotel booking demand.

## Files in Repository

- `dataform_project/`: Contains all the code related to the Dataform GCP pipeline, including SQL queries, configuration files, and documentation.
- `README.md`: This file, providing an overview of the project.


## Getting Started

### Prerequisites

To run or modify this project, you'll need the following tools and services:

- **Dataform GCP**: To run and manage the data pipeline.
- **GitHub Account**: For version control and repository access.
- **Power BI**: To create and view visualizations.

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/hotel-booking-demand-pipeline.git
   cd hotel-booking-demand-pipeline
   ```

2. **Set Up Dataform GCP**:
   - Connect Dataform GCP to your Google Cloud project.
   - Link the cloned repository to your Dataform workspace.
   - Run the pipeline to process the data.

3. **Power BI Connection**:
   - After the pipeline runs, connect Power BI to the final table in your data warehouse.
   - Create your visualizations based on the processed data.

## Visualizations

Visualizations in Power BI will cover various aspects of the hotel booking demand, such as:

- Booking trends over time
- Cancellation rates by customer segment
- Revenue analysis based on booking types and sources
- Customer demographics and booking patterns

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to discuss your ideas.
