# Under-Grad Project Repository
<br>

Hi all there !<br>

Welcome to my Under-Grad Project Repository. This is a store-house of all my projects carried out during my bachelor years at **[VIT University (Vellore, TN, IND)](https://vit.ac.in/)**.

This repo will be beneficial to those (*especially to sophomores, juniors and seniors*) who have just started getting their hands dirty to learn something practically.

> <mark>***NOTE***</mark> : Most of the project's source code is not available because I realized too late that I needed to save it for future reference. Apologies for the inconvenience ! - However, you can still gain a lot from every project's documentation, which is concise and should help you understand the work done.

The projects will help you gain idea about some key sub-realms of `Information Technology` and also the usage of some important tools and platforms. Below is the list of projects in this repository and a summary about them 🔽
<br><br>

### **[Credit Card Fraud Detection System - A Comparison Study on various Machine Learning and Deep Learning Algorithms](https://github.com/sricks404/My-UnderGrad-Projects/tree/main/Credit%20Card%20Fraud%20Detection%20System%20-%20A%20Comparison%20Study%20on%20various%20Machine%20Learning%20and%20Deep%20Learning%20Algorithms) - Soft Computing🔻**<br>

This project aims to address the rising issue of credit card frauds using advanced soft computing and machine learning methods. As digital payments become prevalent, so does the vulnerability to fraud, necessitating robust detection systems.

Key components of the project include :
1.  <b>Objective</b> : To compare the effectiveness of different machine learning and deep learning techniques in detecting credit card fraud using datasets (such as those from Kaggle).<br>
2.  <b>Techniques Used</b> : The study evaluates 7 modules/techniques🔻 <br>
	• [Convolutional Neural Network (CNN)](https://www.ibm.com/topics/convolutional-neural-networks)<br>
	• [Decision Tree Algorithm](https://www.ibm.com/topics/decision-trees)<br>
	• [K Nearest Neighbour (KNN)](https://www.ibm.com/topics/knn#:~:text=The%20k%2Dnearest%20neighbors%20(KNN,used%20in%20machine%20learning%20today.))<br>
	• [Support Vector Machine (SVM)](https://www.ibm.com/topics/support-vector-machine#:~:text=What%20are%20SVMs%3F,in%20an%20N%2Ddimensional%20space.)<br>
	• [Naïve Bayes Classifier](https://www.ibm.com/topics/naive-bayes)<br>
	• [Random Forest Algorithm](https://www.ibm.com/topics/random-forest#:~:text=Random%20forest%20is%20a%20commonly,both%20classification%20and%20regression%20problems.)<br>
	• [Artificial Neural Network (ANN)](https://www.geeksforgeeks.org/artificial-neural-networks-and-its-applications/)<br>
	• [Confusion Matrix](https://www.sciencedirect.com/topics/engineering/confusion-matrix#:~:text=A%20confusion%20matrix%20represents%20the,by%20model%20as%20other%20class.)<br><br>
	>NOTE : Confusion Matrix is not an algorithm - it's just a technique for summarizing the performance of a classification algorithm.

<br>

3.  <b>Evaluation Metrics</b> : Performance is measured using metrics such as [Accuracy, Precision, Recall (Sensitivity), and F1-score](https://klu.ai/glossary/accuracy-precision-recall-f1) to assess the models' effectiveness in fraud detection.<br>
4.  <b>Methodology</b> : The project involves training models on datasets, evaluating their performance using specified metrics, and comparing results with existing studies to determine the most efficient techniques.<br>
5.  <b>Significance</b> : Given the significant increase in credit card fraud cases globally, this research is crucial for identifying the most reliable methods for fraud detection, thereby enhancing security measures in digital transactions.

This project utilized a dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) sourced from Kaggle, specifically provided by Google. This dataset contains records of approximately 284,807 transactions across European countries. Of these transactions, only 492 (0.17%) were identified as fraudulent, highlighting the imbalance between fraudulent and valid transactions. All features in the dataset are numerical, facilitating analysis using various machine learning and deep learning techniques. The 'Amount' feature represents the transaction amount and can be crucial for cost-sensitive learning, while the 'Class' feature serves as the response variable, taking the value 1 for fraud and 0 otherwise. The entire project was implemented in Python 3.9.4 within the [VS Code](https://code.visualstudio.com/) [Python](https://www.python.org/) [Jupyter Notebook](https://jupyter.org/) environment using [Anaconda's](https://www.anaconda.com/) virtual environment. The columns labeled V1 to V28 in the dataset represent values resulting from [Principal Component Analysis (PCA) transformation](https://www.geeksforgeeks.org/principal-component-analysis-pca/). PCA is a method used for dimensionality reduction in datasets, originating from linear algebra. It transforms original variables into weighted linear combinations of those variables, capturing maximum variance while minimizing correlations between them. In PCA, [eigenvectors and eigenvalues](https://lpsa.swarthmore.edu/MtrxVibe/EigMat/MatrixEigen.html) derived from the covariance matrix of the original data are used to create new orthogonal components. An eigenvector of a linear transformation is a vector that changes only by a scalar factor when the transformation is applied, with the corresponding eigenvalue scaling the eigenvector. Among the models examined, `Artificial Neural Network (ANN)` achieved the `highest Accuracy` (<mark><b><u>`99.95%`</u></b></mark>), while `Convolutional Neural Network (CNN)` had the lowest (<mark><b><u>`93.65%`</u><b></mark>). `SVM` demonstrated the `highest Precision` (<mark><b><u>`100.00%`</u></b></mark>), and `ANN excelled in Recall` (<mark><b><u>`99.98%`</u></b></mark>) and `F1 Score` (<mark><b><u>`99.97%`</u></mark></b>). Overall, `ANN` proved to be the `most effective method`, showcasing superior performance in training, testing, and application. Future enhancements could focus on expanding datasets to further improve model accuracy, potentially reducing false positives and enhancing fraud detection capabilities significantly.
<br>
<br>

### **[Stock Market Prediction](https://github.com/sricks404/My-UnderGrad-Projects/tree/main/Stock%20Market%20Prediction) - Data Mining🔻**<br>

This project focuses on predicting [Tata Steel stock prices](https://www.kaggle.com/datasets/bibinvargheset/tatasteel) using linear regression and decision tree regression, leveraging Python and libraries such as [Numpy](https://numpy.org/), [Matplotlib](https://matplotlib.org/stable/), [Pandas](https://pandas.pydata.org/), and [Sci-Kit Learn](https://scikit-learn.org/stable/) on [Google Colab](https://colab.research.google.com/). The primary goal is to forecast stock prices by analyzing historical data, assisting investors in making informed decisions about buying or selling stocks despite the challenges posed by numerous influencing factors like a company's financial status and national policies. The project treats the prediction problem as a [regression](https://www.geeksforgeeks.org/regression-in-machine-learning/) task, highlighting the effectiveness of data mining techniques in producing accurate stock price forecasts. The methodology involves steps such as importing necessary modules, reading and cleaning the dataset, visualizing data, splitting the dataset, predicting future values, and evaluating predictions using [Root Mean Square Error (RMSE)](https://c3.ai/glossary/data-science/root-mean-square-error-rmse/), [Mean Absolute Error (MAE)](https://medium.com/@m.waqar.ahmed/understanding-mean-absolute-error-mae-in-regression-a-practical-guide-26e80ebb97df), and [Mean Squared Error (MSE)](https://www.geeksforgeeks.org/mean-squared-error/) metrics. [Linear regression](https://www.geeksforgeeks.org/ml-linear-regression/), which finds the best-fit line for data points, and [decision tree regressor](https://www.geeksforgeeks.org/python-decision-tree-regression-using-sklearn/), which uses a flowchart-like structure for decision-making, were used as the primary algorithms. The evaluation showed that linear regression had an `RMSE` of `9.3406`, `MAE` of `87.2485`, and `MSE` of `12061.9769`, while the decision tree regressor had an `RMSE` of `9.3444`, `MAE` of `87.3190`, and `MSE` of `12078.8146`, indicating that linear regression was slightly more efficient by a margin of `0.0038%` based on `RMSE`. The project concludes that linear regression is marginally more accurate for this dataset, providing the authors with valuable insights into the implementation and evaluation of these algorithms in stock market prediction. 
<br><br>

### **[COVID 19 : Self Heath Analysis](https://github.com/sricks404/My-UnderGrad-Projects/blob/main/COVID_19-Self-Health-Analysis%20(Web%20Technologies).pdf) - Web Technologies🔻**<br>
 
 The project is a web application designed to provide a pre-testing platform for users to assess their health status for potential COVID-19 symptoms before seeking further medical testing. The application aims to help manage healthcare needs by offering an initial self-assessment tool for a large population. Users can register for free to receive updates and notifications, with registered users receiving an email if their health status indicates a need for immediate testing and medical attention. Technically, the project employs [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS](https://www.w3schools.com/css/), [JavaScript](https://www.w3schools.com/js/), [jQuery](https://www.w3schools.com/jquery/default.asp), and [AngularJS](https://www.w3schools.com/angular/) for the <b>frontend</b>, with [NodeJS](https://www.w3schools.com/nodejs/nodejs_intro.asp) and [ExpressJS](https://www.geeksforgeeks.org/express-js/) for the <b>backend</b>, and [MongoDB](https://www.mongodb.com/) as the <b>database</b>. The application includes four main pages: `Page 1` provides pandemic updates, guidelines for social distancing, hand sanitizing, and mask-wearing, and includes a link for unregistered users to analyze their health status. `Page 2` features a registration form with validation using JavaScript, jQuery, and AngularJS, and buttons for form submission and navigation to the analysis page. `Page 3` is the login page for existing users with validation and an alert displaying the username upon entry. `Page 4` is the main assessment page where users answer questions about their health, recent activities, and potential exposure to the virus; responses are recorded, and users receive feedback. The application ensures a smooth user experience with form validation and feedback mechanisms, including color changes upon option selection and the ability to reset responses by refreshing the page. The backend, built with NodeJS and ExpressJS, and MongoDB as the database, includes a `server.js` file for server operations and a database collection named `UserDetails` to store user data. This comprehensive and functional web application aids in the early detection of COVID-19 symptoms, contributing to public health efforts during the pandemic.
<br>
<br>

### **[Facial Image Suppression to Maintain Data Privacy](https://github.com/sricks404/My-UnderGrad-Projects/blob/main/Facial%20Image%20Supression%20using%20Data%20Privacy%20(Network%20and%20Information%20Security).pdf) - Network and Information Security🔻**
This project focuses on developing a method to anonymize facial images for privacy protection, particularly in the context of video surveillance. Traditional de-identification techniques, like <i>[blurring](https://medium.com/@kenrobbins/call-for-image-de-identification-standards-6b33e6576a12)</i> or <i>[black-boxing](https://openaccess.thecvf.com/content_ICCVW_2019/papers/HBU/Yan_Attributes_Preserving_Face_De-Identification_ICCVW_2019_paper.pdf)</i>, are inadequate in preserving privacy without compromising image quality. The proposed method involves using blended facial composites to obscure identities while retaining key facial features. The project highlights the dramatic increase in data sharing online and the necessity for privacy protection against unauthorized access and misuse of facial images. The proposed model describes an approach to de-identifying images using a modified averaging technique and storing these images in a database. The method uses facial landmark detection to map key facial features. Implementation utilizes Python and the [dlib library](http://dlib.net/) to extract facial landmarks and apply the de-identification process, including specific functions for transforming images, color-coding features, and recognizing facial features. The results and discussion section compares the proposed method with traditional black-boxing, demonstrating superior performance in terms of non-detection accuracy by face recognition software. The proposed method achieves an `80%` accuracy rate of non-detection compared to `20%` for black-boxing. Additionally, the recovery function accurately reconstructs the original images with a [confidence level](https://machinelearningmastery.com/confidence-intervals-for-machine-learning/) of `85.08%` using the [Kairos tool](https://face.kairos.com/). The project concludes that the modified averaging technique effectively de-identifies and recovers images, outperforming traditional methods. Future work includes developing a transmission medium for secure image suppression and recovery. The project showcases an innovative approach to balancing privacy and image quality, with potential applications in surveillance and other areas requiring secure facial image handling.
<br>
<br>

### **[Library Management System](https://github.com/sricks404/My-UnderGrad-Projects/blob/main/Library%20Management%20System%20(C%20Programming).pdf) - C Programming🔻**<br>

This project is an advanced C programming application aimed at simplifying library operations. The system incorporates key C programming concepts like structures, file handling, strings, arrays, pointers, functions, loops, and conditional statements. The application is menu-driven and offers several functionalities: displaying a welcome message, user authentication, adding books to the database, searching for books, viewing book information, deleting books, and updating user credentials. Upon launch, users see a welcome screen and proceed to a login page, where incorrect credentials entered thrice lead to a login failure message. The main menu provides options for managing books and user credentials, including adding book details such as <i>Book ID, Book Name, Author Name, Student Name, Date of adding, Searching for books by Name, Viewing all books with full details, Deleting books by Book ID, and Updating user passwords</i>. Users can exit the application after completing their tasks. The system ensures efficient and organized library management, reducing the complexity and confusion associated with traditional methods.
<br>
<br>

### **[Library Management System](https://github.com/sricks404/My-UnderGrad-Projects/blob/main/Library%20Management%20System%20(DBMS).pdf) - Database Management System (DBMS)🔻**<br>

This project aims to modernize traditional library systems by designing and implementing a comprehensive database to streamline library operations. This system addresses the limitations of manual record-keeping by ensuring data safety, ease of access, and efficient management of books and user records. It features functionalities such as real-time book availability, overdue fine tracking, and user management. The database includes entities for <i>libraries, branches, books, authors, publishers, staff, borrowers, and visitors</i>, with specified relationships and constraints. The project outlines scenarios for <i>data removal, updates, and retrievals</i>, ensuring robust database interactions. Additionally, it details the creation of [SQL](https://www.w3schools.com/sql/) queries and [PL/SQL](https://www.geeksforgeeks.org/plsql-introduction/) functions and procedures to demonstrate the system's capabilities in handling complex data operations, using [Oracle database 11g](https://www.oracle.com/database/technologies/database-11g-express-edition.html) database platform.
<br>
<br>

### **[Student Behavioral Analysis via Emotional Speech Recognition](https://github.com/sricks404/My-UnderGrad-Projects/blob/main/Student%20Behavioral%20Analysis%20via%20Emotional%20Speech%20Recognition%20(Machine%20Learning).pdf) - Machine Learning 🔻**<br>
This project aims to analyze and predict the emotions expressed by students during their interactions with teachers in online classes. ​ The goal is to understand the students' understanding of the topics being taught based on their tone of speech. ​ The project focuses on recognizing emotions such as <i>neutral, anger, joy, and sorrow</i> from the students' spoken replies. ​This project follows a technical explanation path and involves several steps and techniques. ​ Data augmentation is used to generate fresh training examples by adding tiny perturbations to the original dataset. ​ Four data augmentation strategies are employed : <i><u>noise, shifting, pitch shifting, and time stretching</u></i>. ​ These techniques are applied to the audio data before generating [Mel Frequency Cepstral Coefficients (MFCC) features](https://medium.com/@derutycsl/intuitive-understanding-of-mfccs-836d36a1f779), which are used to train the deep learning model. The MFCC feature extraction technique involves several steps such as <i>[pre-emphasis](https://jonathan-hui.medium.com/speech-recognition-feature-extraction-mfcc-plp-5455f5a69dd9), [framing](https://medium.com/@tanveer9812/mfccs-made-easy-7ef383006040), [windowing](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.aircconline.com/sipij/V4N4/4413sipij08.pdf), [Fast Fourier Transform (FFT)](https://medium.com/swlh/the-fast-fourier-transform-fft-5e96cf637c38), [Mel Scale Filter Bank](https://vtiya.medium.com/mfcc-801a9fa53617), low-energy computation, and [Discrete Cosine Transform (DCT)](https://medium.com/@derutycsl/intuitive-understanding-of-mfccs-836d36a1f779)</i>. ​ These steps help transform the audio recordings into a format that the model can understand. ​This project utilizes a [Convolutional Neural Network (CNN)](https://towardsdatascience.com/convolutional-neural-networks-explained-9cc5188c4939) model for speech recognition. ​ The model receives training data, including expression labels, and undergoes intensity normalization. ​ The data is then split into train and test groups, and the CNN model is built and trained using the training data. ​ The trained model is used to predict the emotions expressed in the students' speech. ​This project references several research studies that have explored similar topics, including the use of [hybrid neural networks](https://medium.com/the-modern-scientist/exploring-the-potential-of-hybrid-deep-neural-networks-8e013ea0bafe), [deep neural networks](https://www.sciencedirect.com/topics/computer-science/deep-neural-network), and CNN algorithms for speech emotion recognition. ​ The studies highlight the use of different datasets, data augmentation techniques, and feature extraction methods to improve the accuracy of emotion recognition. ​This project includes code implementation and analysis, including data visualization, data augmentation, MFCC extraction, model training, and evaluation. ​ The results of testing the trained model on the testing dataset are summarized in a table, showing the testing accuracy for various emotions. ​In conclusion, this project demonstrates the effectiveness of the CNN model in recognizing emotions from students' speech. ​ The overall accuracy of the model is <mark><b>`87.80%`</b></mark>, with higher accuracy observed for female emotions compared to male emotions. ​ The project highlights the potential of using machine learning techniques to analyze student behavior and emotions in online learning environments.
