## Transformative Data Pipeline for Civil Engineering: An Imagine Cup 2024 Proposal

### Executive Summary

In the rapidly evolving world of civil engineering, data remains a cornerstone of innovation and efficiency. However, a significant gap exists in the digital transformation of data handling within the industry. Our proposal for the Imagine Cup 2024 is a sophisticated pipeline designed to transform archaic data sheets—predominantly paper-based or PDF files—into structured, actionable data frames. Our application aims to revolutionize communication between various stakeholders in civil engineering by seamlessly digitalizing their inter-company documentation.

### The Problem

Currently, companies in the civil engineering sector often work in silos, with data documentation scattered across different formats, including paper and non-interactive digital files like PDFs. Although these companies may consider the scanning of documents as their best effort toward digitalization, this method falls short of leveraging the information for analytics and automation.

### The Solution

Our solution is a robust application tailored to the civil engineering domain. This tool will:

- Digitize documents such as soil investigation sheets from geologists and concrete compressive strength reports from laboratories.
- Employ machine learning to convert unstructured data from these documents into structured data frames compatible with data analysis tools.
- Customize documentation intelligence models to recognize and process industry-specific documents, enhancing the accuracy and utility of the transformed data.

### The Innovation

At the heart of our application is a machine learning (ML) model trained on a diverse dataset of civil engineering documents. By leveraging state-of-the-art ML techniques, our model will learn to interpret various document formats and extract valuable insights, thus bridging the digital divide in data communication.

### Development Plan

For the initial stage of the competition, we aim to create a prototype that:

- Demonstrates the core functionality of scanning and digitizing paper-based documents.
- Illustrates the ML model's potential using a sample dataset from the civil engineering department's library.

We understand that a fully functional product is not required for the first deadline. However, we intend to present a compelling proof of concept that showcases the feasibility and impact of our solution.

### Industry Impact

Our product falls squarely within the 'Industry Solution' category, offering a bespoke tool that can significantly enhance efficiency, accuracy, and collaboration across the civil engineering sector. By digitizing and structuring data, we unlock the potential for advanced analytics, predictive modeling, and AI-driven decision-making.

### Merit of this idea:

1. **Industry-Specific Innovation**: Tailoring a solution specifically to civil engineering—considering its unique documentation and data requirements—shows a deep understanding of the industry and presents a bespoke solution rather than a one-size-fits-all approach.

2. **Machine Learning Application**: The use of machine learning to customize document intelligence for industry-specific documents is a sophisticated approach that demonstrates innovation in artificial intelligence and its practical applications.

3. **Process Transformation**: By converting traditional paper and PDF files into structured data frames, you are transforming the fundamental processes of communication and data analysis within civil engineering, which can lead to a paradigm shift in how the industry operates.

4. **Enhanced Decision-Making**: The potential inclusion of analytics and predictive modeling tools can significantly enhance decision-making capabilities within the industry, leading to better outcomes in terms of cost, efficiency, and risk management.

5. **Collaborative Digitalization**: The idea promotes a collaborative approach to digitalization, urging different stakeholders to come together and share data more efficiently, which is creative in fostering a more integrated industry community.


---
## Backend (Buji)

- Customized document intelligence data retrieval
	- Our model will be customized for civil engineering log-sheet, and the model will be able to recognize numbers in either hand-writing or printed format.  

- Unique feature set
	- Smart document tagging and retrieval:
		- Use AI to tag documents based on content, making it easier for users to search for and retrieve specific documents or data points.
	- Customizable Data Views for Different Stakeholders: 
		- (Put it on the report, but not coding it)
		- Allow users to create customizable views of data that are relevant to their role in the project, whether they are field engineers, project managers, or clients.
	- Abnormal data detection
		- Use rule-based and ML method to detect whether there are some abnormal data inputs generated by construction worker or data-transformation process of the model

Actionable list:
1. Create an azure account and try to run their model (Approx: 0.5 hour)
2. try their customization functions and see the changes. (Approx: 1 hour)
3. Figure out how to evaluate and validate the performance of the ML model. (Approx. 0.5 hour)
4. Package the customized ML model for deployment (Approx. 0.5 hour)
5. Create a cloud resource / API / similar thing so that our app can connect with the customized model  (Approx: 0.5 hour)
6. Abnormal data detection: Use rule-based and ML method to detect whether there are some abnormal data inputs generated by construction worker or data-transformation process of the model (Approx: 0.5 hour)
7. Smart document tagging: Use AI to tag documents based on content, making it easier for users to search for and retrieve specific documents or data points. (Approx: 1 hour)

### Conclusion

In the spirit of innovation championed by the Imagine Cup, our team is committed to developing a tool that not only meets the current needs of the civil engineering industry but also paves the way for future advancements. We are confident that the judges will recognize the potential of our idea and allow us to proceed to the second stage for further development.


---

### User Experience Design (UXD) (Latisha)

## Actionable list

When delegating tasks to a front-end developer, it's important to provide a comprehensive list of actionable items that cover various aspects of the web application's development. Here is a structured list you can pass along:

### Front-End Development Actionable Items

Certainly! Below is a structured list of actionable items for your front-end developer to follow in line with your transformative data pipeline proposal:

### Front-End Development Actionable Items

1. **Initial Setup**: 
   - Set up a development environment with the necessary tools (IDE, Git, etc.).
   - Install front-end development frameworks and libraries (e.g., React, Angular, Vue.js).
   - Ensure proper integration with Azure services and APIs.

2. **User Interface Design**:
   - Create wireframes and mockups for the application's user interface, focusing on usability for civil engineering professionals.
   - Implement a responsive design to ensure compatibility with various devices (desktop, tablet, mobile).

3. **Document Upload Feature**:
   - Develop a user-friendly document upload system to allow users to submit paper-based documents or PDF files.
   - Implement a preview feature that lets users verify uploaded documents before processing.

4. **Progress Indicators**:
   - Design and implement progress indicators for document scanning and data extraction processes to provide real-time feedback to users.

5. **Results Display**:
   - Create dynamic views to display structured data frames resulting from the ML model's processing.
   - Ensure these views are clear, readable, and exportable (e.g., export to CSV, Excel).

6. **Customizable Data Views**:
   - (As noted for backend, but front-end needs to prepare UI/UX for this) Develop the front-end component for customizable data views, ensuring a seamless user experience when this feature is implemented.

7. **Search and Retrieval**:
   - Implement a search function to enable users to find documents or specific data points quickly.
   - Integrate the AI-based tagging system from the backend to improve search efficiency.

8. **User Authentication and Authorization**:
   - Set up secure user authentication to protect sensitive data.
   - Implement role-based access control to ensure users see data relevant to their role.

9. **Abnormal Data Indicators**:
   - Develop visual cues (e.g., color-coded alerts, icons) to flag abnormal data as indicated by the backend.

10. **Real-time Collaboration**:
    - Implement features that allow multiple users to work on the same document or dataset simultaneously.
    - Enable comment and annotation features for collaborative review.

11. **Feedback Loop**:
    - Design a system for users to provide feedback on the ML model's accuracy in data extraction, such as a 'report issue' feature.

12. **Performance Evaluation**:
    - Create a dashboard or similar interface that allows users to visualize the ML model's performance metrics provided by the backend.

13. **Documentation and User Help**:
    - Write user guides and help documentation integrated within the app for self-service assistance.
    - Design tooltips and walkthroughs for first-time users to aid in navigation and feature utilization.

14. **Testing and Validation**:
    - Conduct front-end unit tests and integration tests with the backend services.
    - Coordinate with the backend team for end-to-end testing of the application.

15. **Deployment and Continuous Integration**:
    - Set up a process for continuous integration and deployment (CI/CD) of front-end changes.
    - Ensure the application is deployable to the cloud environment and is scalable.

16. **Accessibility Compliance**:
    - Ensure the application meets web accessibility standards to accommodate all users, including those with disabilities.

17. **Localization**:
    - Prepare the application for potential localization if the service is to be used in different regions with different languages.

---
## Application architecture (Grand)

For your web app proposal using Azure, you will need a variety of components to manage the application, data processing, storage, and machine learning functionalities. Here is a breakdown of the components you might consider using:

### Azure Components

#### 1. App Service
- **Purpose**: To host your web application.
- **Reason**: Azure App Service is a fully managed platform for building, deploying, and scaling web apps. It supports multiple languages and frameworks, such as .NET, Node.js, Java, Python, or PHP.

#### 2. Azure Cognitive Services
- **Purpose**: To incorporate AI capabilities such as document intelligence and data extraction.
- **Reason**: Azure Cognitive Services can provide pre-built AI functionalities that you can integrate with your application. For instance, the Form Recognizer service can analyze text in your documents and return a structured data output.

#### 3. Azure Machine Learning
- **Purpose**: To train and deploy your custom ML models.
- **Reason**: Azure Machine Learning is a cloud-based environment you can use to train, deploy, manage, and track machine learning models. You can train models on a diverse dataset of civil engineering documents as mentioned in your proposal.

#### 4. Azure Functions
- **Purpose**: To run serverless computations.
- **Reason**: Azure Functions can help in processing data, running ML models, or any other compute tasks that need to be triggered by events without the need for a full app service.

#### 5. Azure Blob Storage
- **Purpose**: To store unstructured data such as documents and logs.
- **Reason**: Blob Storage is ideal for storing large amounts of unstructured data. You can use it to store documents before and after processing.

#### 6. Azure Cosmos DB or Azure SQL Database
- **Purpose**: To maintain structured data outputs.
- **Reason**: Cosmos DB is a globally distributed, multi-model database service for managing data at scale. It is suitable for applications with variable schemas and high throughput. Azure SQL Database is a fully managed relational database with auto-scale, integral intelligence, and robust security.

#### 7. Azure Search
- **Purpose**: To enable smart document tagging and retrieval.
- **Reason**: Azure Cognitive Search is an AI-powered cloud search service for mobile and web app development. It can be used to index large amounts of content in a searchable format.

#### 10. Azure DevOps
- **Purpose**: For CI/CD pipelines and project management.
- **Reason**: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications.

#### 11. Azure Security Center
- **Purpose**: To reinforce security.
- **Reason**: Azure Security Center provides unified security management and advanced threat protection across hybrid cloud workloads.

### Additional Considerations

- **API Management**: If your application is going to expose APIs, you might need Azure API Management to create consistent and modern API gateways for back-end services.
- **Azure Active Directory (AAD)**: For identity management and access control. You can use it for authenticating and authorizing users to access your application or parts of your app.

#### Deployment and Management Tools

- **Azure Resource Manager (ARM) templates or Terraform**: For infrastructure as code, to automate the deployment of your Azure resources.
- **PowerShell and Azure CLI**: For scripting and automating tasks in Azure.