<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>🏠 HousePricer</h1>

  <p>
    HousePricer is a machine learning project designed to predict housing prices based on various features. It incorporates multiple regression algorithms and provides a web interface for user interaction.
  </p>

  <h2>📌 Project Overview</h2>
  <ul>
    <li>Implements several regression models including Linear Regression, Lasso, ElasticNet, KNN, Polynomial Regression, LGBM, and ANN.</li>
    <li>Utilizes the <code>USA_Housing.csv</code> dataset for training and evaluation.</li>
    <li>Provides a web application interface for users to input data and receive price predictions.</li>
  </ul>

  <h2>📁 Dataset Description</h2>
  <p>
    The project uses the <code>USA_Housing.csv</code> dataset, which contains features such as:
  </p>
  <ul>
    <li>Average Area Income</li>
    <li>Average Area House Age</li>
    <li>Average Area Number of Rooms</li>
    <li>Average Area Number of Bedrooms</li>
    <li>Area Population</li>
    <li>Price (Target Variable)</li>
  </ul>

  <h2>🧰 Methodology</h2>
  <ol>
    <li><strong>Data Preprocessing</strong>
      <ul>
        <li>Handling missing values and outliers.</li>
        <li>Feature scaling for model compatibility.</li>
      </ul>
    </li>
    <li><strong>Model Training</strong>
      <ul>
        <li>Training various regression models on the dataset.</li>
        <li>Saving trained models as pickle files for deployment.</li>
      </ul>
    </li>
    <li><strong>Model Evaluation</strong>
      <ul>
        <li>Assessing performance using metrics like R-squared, Mean Squared Error, etc.</li>
        <li>Storing evaluation results in <code>model_evaluation_results.csv</code>.</li>
      </ul>
    </li>
    <li><strong>Web Deployment</strong>
      <ul>
        <li>Developing a web application using Flask.</li>
        <li>Creating HTML templates: <code>index.html</code>, <code>model.html</code>, and <code>results.html</code>.</li>
        <li>Integrating trained models for real-time predictions.</li>
      </ul>
    </li>
  </ol>

  <h2>🚀 Getting Started</h2>
  <h3>Prerequisites</h3>
  <ul>
    <li>Python 3.x installed on your system.</li>
    <li>Required Python libraries:
      <ul>
        <li>pandas</li>
        <li>numpy</li>
        <li>scikit-learn</li>
        <li>Flask</li>
      </ul>
    </li>
  </ul>

  <h3>Installation</h3>
  <pre><code>git clone https://github.com/kunalmahadule/HousePricer.git
cd HousePricer
pip install -r requirements.txt</code></pre>

  <h3>Running the Web Application</h3>
  <pre><code>python app.py</code></pre>
  <p>
    Open your web browser and navigate to <a href="http://localhost:5000">http://localhost:5000</a> to access the application.
  </p>

  <h2>📂 Project Structure</h2>
  <pre><code>├── ANN.pkl
├── ElasticNet.pkl
├── KNN.pkl
├── LGBM.pkl
├── LassoRegression.pkl
├── LinearRegression.pkl
├── PolynomialRegression.pkl
├── USA_Housing.csv
├── app.py
├── index.html
├── model.html
├── model.py
├── model_evaluation_results.csv
├── results.html
└── README.md</code></pre>

  <h2>🤝 Contributing</h2>
  <p>Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.</p>

</body>
</html>
