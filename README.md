# Ashish Pandey

Welcome to my portfolio website! This site showcases my skills, projects, and professional experience in data science and machine learning. You can find detailed information about my background, education, and projects below.

## About Me

I am a passionate Data Science Master’s student at the New Jersey Institute of Technology. My academic and research journey has been focused on exploring innovative solutions in machine learning, deep learning, and natural language processing. Specifically, I am interested in developing faster alternatives to transformers by leveraging state-space models. As a Research Assistant, I have worked on projects ranging from dynamic graph embedding to Alzheimer’s disease prediction, where I have developed models like DG-Mamba that push the boundaries of existing technologies.

Beyond research, I have practical experience in cloud infrastructure optimization, data pipeline implementation, and software development from my time at Accenture. I am deeply committed to advancing research that not only challenges the status quo but also has a tangible, positive impact on human well-being. Through my work, I strive to contribute to fields that can make a difference in the world.

- **LinkedIn:** [linkedin.com/in/ashish-pandey-005239315](https://www.linkedin.com/in/ashish-pandey-005239315/)
- **GitHub:** [github.com/Dettrax](https://github.com/Dettrax)

## Skills

- **Programming Languages:** Python, Java, C++, R, SQL
- **Data Processing:** PySpark, Pandas, numpy, ETL, Data science pipeline
- **Machine Learning & AI:** Tensorflow, Pytorch, Natural language processing, Bayesian Networks, Gaussian Process, SVMs, Random Forests, Isolation Forests
- **Deep Learning:** DNN, CNN, RNN, LSTM, ESN
- **Cloud Computing:** AWS, Hadoop, Cloud Computing, Cloudera
- **Web Development:** Flask, RESTful API
- **DevOps & CI/CD:** Git, Terraform, Datadog, DevOps (CI/CD), Kubernetes, Agile, MLFlow
- **Data Visualization:** matplotlib, Power BI, Tableau, Data Visualization, Statistical Analysis
- **Testing & Experimentation:** A/B testing
- **Data Tools:** MS Excel, Information retrieval, Data scraping, selenium, Statistics, dynamic programming

## Education

**Master's in Data Science | GPA: 3.75 / 4.0**  
New Jersey Institute Of Technology, Newark, NJ  
September 2023 - May 2025

## Projects

### [Prudential Dataset](https://github.com/Dettrax/PrudentialDataset)
![Prudential Dataset](assets/imgs/prud.webp)
Led a risk assessment optimization project for Prudential Life Insurance, developing a machine learning algorithm to assign risk factors using minimal customer data. Utilized Principal Component Analysis (PCA) and boosting algorithms on a 2015 dataset, achieving top Kaggle performance with 23% fewer features, while maintaining significant variance retention.

### [Malaria Topic Modelling Project in R](https://github.com/Dettrax/malaria-articles-analysis)
![Malaria Topic Modelling](assets/imgs/malaria.webp)
Developed and implemented a data processing pipeline to systematically extract, clean, and organize data from a vast collection of malaria-related articles. Utilized clustering and natural language processing (NLP) techniques to identify main themes and significant keywords, revealing prevalent research areas and enhancing insights into the malaria landscape.

### [Multimodal Forecasting Model for Stock Price Prediction](https://github.com/Dettrax/multimodal-forecasting-model-for-stock-price-prediction)
![Stock Price Prediction](assets/imgs/stock-pred.webp)
Developed an advanced oil price prediction system combining ARIMA and GARCH models for price and volatility Time Series forecasting, respectively. Achieved a 17% performance enhancement over traditional attention mechanisms by integrating the novel MAMBA model. Optimized system performance with LSTM models via Optuna, incorporating XGBoost and leveraging historical data and news sentiments for improved predictive accuracy.

## Conference/Talks
- Presented research work "A Comparative Study on Dynamic Graph Embedding based on Mamba and Transformers"
 at SEA-CROGS 2024, Stanford University.
  
## Professional Experience

### Teaching Assistant - Deep learning (DS 677) | NJIT | Newark, NJ
**September 2024 - Present**
- Grading , Doubt Solving and project managment.

### Research Assistant | NJIT | Newark, NJ
**May 2024 - August 2024**
- Developed and implemented DG-Mamba and GDG-Mamba, an innovative adaptation of the Mamba architecture for dynamic graph embedding, integrating selective state space models to capture complex temporal dependencies. Achieved superior performance compared to [TransformerG2G](https://arxiv.org/abs/2307.02588) on the Temporal Graph Benchmarks , demonstrating improved ability to model long-range interactions and adaptive time-stepping in evolving graph structures.
- Engaged in cutting-edge research on Alzheimer's disease prediction using Wulver's High-Performance Computing system, applying advanced deep learning models and selective state-space analysis to fMRI data. This work is poised to transform diagnostic approaches by enhancing early detection capabilities.
- Leading the development of an innovative hierarchical encoder for JAMBA models, specifically tailored for embedding in hyperbolic spaces. This research aims to revolutionize the handling and analysis of complex network data by leveraging the unique properties of hyperbolic geometry, potentially enhancing the accuracy and efficiency of data representation in LLM applications.


### Associate Data Engineer | Accenture | Mumbai, IN
**July 2021 – April 2023**
- Spearheaded the migration of 9 critical microservices to AWS cloud infrastructure for a major insurance client, enhancing API request handling capacity from 3,000 to 20,000 records per day, significantly improving system scalability and operational efficiency.
- Designed and implemented a robust PySpark data processing pipeline on AWS State Machine, managing the daily processing of over 20,000 records. Established RDS databases for efficient handling of liability data during migrations, ensuring data integrity and seamless operations.
- Modernized legacy Java code by transitioning RESTful API projects to Python, optimizing them to meet AWS Lambda’s 15-minute execution window. Developed and maintained CI/CD pipelines using GitLab, enhancing the speed and reliability of microservice deployments.
- Led the development and deployment of Python packages, utilizing CI/CD pipelines for systematic management on JFrog. Implemented Datadog dashboards to monitor cloud resource utilization, resulting in improved error detection and handling through monitoring of Lambda, Redshift, State Machine, S3, Glue Jobs, SNS, and SQS.
- Mentored junior engineers and conducted training sessions on cloud technologies and best practices, fostering a culture of continuous learning and improvement within the team.

## Publications

### A Comparative Study on Dynamic Graph Embedding based on Mamba and Transformers
This paper delves into the exciting field of dynamic graph embedding, which is crucial for understanding the evolving nature of networks in various domains. The key focus of my research was to address the scalability limitations of transformer-based models, which, despite their ability to capture long-range dependencies in temporal graph data, face challenges due to their quadratic computational complexity.

To tackle this, I introduced three novel models: TransformerG2G with graph convolutional networks, DG-Mamba, and DG-Mamba with graph isomorphism network edge convolutions. The DG-Mamba models leverage the state space model architecture, specifically the Mamba model, known for its linear complexity and efficiency in handling long sequences.

Through extensive experiments on multiple benchmark datasets, I demonstrated that my Mamba-based models achieve comparable or even superior performance to transformer-based approaches [TransformerG2G](https://arxiv.org/abs/2307.02588) in link prediction tasks. Importantly, they offer significant computational advantages, especially when dealing with longer sequences. The DG-Mamba variants consistently outperformed transformer-based models on datasets with high temporal variability, showcasing their ability to capture complex temporal patterns effectively.

Furthermore, I provided insights into the learned temporal dependencies by analyzing attention weights and state matrices, further highlighting the models' capabilities. By effectively combining state-space models with graph neural networks, my work addresses key limitations of previous approaches and contributes to the advancement of efficient temporal graph representation learning.

In conclusion, my research offers promising directions for scaling dynamic graph embedding to larger, more complex real-world networks. This has the potential to enable new applications in diverse areas such as social network analysis, financial modeling, and biological system dynamics. The Mamba-based models I introduced present a valuable tool for researchers and practitioners working with time-evolving networks, paving the way for more efficient and effective analysis of complex systems.
- **Read the paper here:** [DG-Mamba](https://arxiv.org/abs/2412.11293)


### Xenia – A Smart Tour Planning And Recommendation Using Crowdsourced Data
The paper "Xenia - A Smart Tour Planning And Recommendation Using Crowdsourced Data" presents the design and implementation of a mobile application aimed at enhancing the tour planning experience for users. The app leverages technologies like AI, NLP, and recommender systems to provide personalized tour recommendations and streamline the planning process. The key features of the app include:

- Personalized Recommendations: The app utilizes a recommender system that takes into account user preferences such as climate, budget, travel method, and trip duration to suggest suitable tour destinations.

- Virtual Tour Guide: Once a tour is selected, the app offers a virtual tour guide feature that utilizes live interactive maps to guide users through the tour, providing information about various checkpoints along the way.

- Shopping Recommendations: The app also includes a shopping tab that suggests items based on the user's current location, promoting local businesses and enhancing the overall tour experience.

- Crowdsourced Data: The app's recommender system is powered by NLP techniques that analyze past user reviews and social media data to extract relevant information about tours, ensuring recommendations are up-to-date and accurate.

- Local Business Integration: The app provides a platform for local businesses to advertise their services to users, fostering a mutually beneficial relationship between tourists and local establishments.

The paper concludes that the Xenia app successfully achieves its goal of providing users with a comprehensive and interactive tour planning experience. By incorporating personalized recommendations, a virtual tour guide, shopping suggestions, and crowdsourced data, the app empowers users to make informed decisions and optimize their travel itineraries. Additionally, the integration of local businesses contributes to the growth of the local economy and enhances the overall tourism ecosystem. The app's user-friendly interface and seamless functionality further contribute to its effectiveness in simplifying the tour planning process and enriching the travel experience for users.


- **Read the paper here:** [IJRAR1CCP011](https://www.ijrar.org/viewfull.php?&p_id=IJRAR1CCP011)


## Leadership and Recognitions

- Awarded "Accenture Growth Catalyst Q1 2022" for delivering excellent performance exceeding expectations.
- Received "Accenture Skill Star Award FY22" for best client feedback from State Farm Insurance.

## Certification

- Bloomberg Market Concepts - [Bloomberg](https://portal.bloombergforeducation.com/certificates/ZPWL3VNUQ7W4WREGK8BQWABX)
- Introduction to Relational Databases (RDBMS) - [IBM](https://www.coursera.org/account/accomplishments/verify/T0MCYV8YQDK0)
- Data Analysis and Visualization with Power BI - [Microsoft](https://www.coursera.org/account/accomplishments/verify/9YP3E3U9ZD18)

## Contact

- **Email:** ap2934@njit.edu
