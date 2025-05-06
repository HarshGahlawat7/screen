<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SafeVoyage AI – Risk Assessment by Harsh Gahlawat</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f7fa;
      color: #333;
    }
    .container {
      max-width: 900px;
      margin: 30px auto;
      background: #ffffff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    h1 {
      text-align: center;
      color: #154c79;
      margin-bottom: 10px;
    }
    h2 {
      color: #1f618d;
      margin-top: 30px;
    }
    h3 {
      color: #117864;
    }
    p {
      line-height: 1.6;
    }
    ul {
      padding-left: 20px;
    }
    li {
      margin-bottom: 8px;
    }
    .highlight {
      background: #d5f5e3;
      padding: 2px 6px;
      border-radius: 4px;
    }
    .section-icon {
      margin-right: 8px;
    }
    .tag {
      background: #eaf2f8;
      color: #154360;
      display: inline-block;
      padding: 4px 8px;
      border-radius: 4px;
      margin: 2px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🚢 SafeVoyage AI – Risk Assessment for Maritime Emergencies</h1>
    <p><strong>By Harsh Gahlawat</strong></p>

    <p>This intelligent system uses a <span class="highlight">Random Forest Classifier</span> to assess survival likelihood during modern maritime evacuations. Inspired by real historical disasters like the Titanic, the model analyzes passenger data (age, class, gender, fare, etc.) to provide actionable insights for <strong>rescue prioritization, emergency drills, and safety policy planning</strong>. Built with an intuitive <strong>Gradio interface</strong>, SafeVoyage AI simulates rescue decisions in real-time, making it a valuable tool for maritime authorities and emergency response strategists.</p>

    <h2>📊 Overview</h2>
    <ul>
      <li><strong>Dataset:</strong> Maritime passenger manifest (<code>tested.csv</code>)</li>
      <li><strong>Model:</strong> Random Forest Classifier</li>
      <li><strong>Interface:</strong> Gradio</li>
      <li><strong>Tech Stack:</strong> Python, Pandas, Scikit-learn, Gradio</li>
    </ul>

    <h2>🚀 Features</h2>
    <ul>
      <li>Preprocessed and cleaned maritime dataset</li>
      <li>Encoded categorical variables</li>
      <li>Trained using a robust Random Forest algorithm</li>
      <li>Real-time risk predictions via web interface</li>
      <li>Modular codebase (training + deployment separated)</li>
    </ul>

    <h2>🧠 Model Details</h2>
    <ul>
      <li><strong>Algorithm:</strong> Random Forest Classifier</li>
      <li><strong>Target:</strong> <code>Survived</code> (0 = Did not survive, 1 = Survived)</li>
      <li><strong>Input Features:</strong>
        <ul>
          <li><code>Pclass</code> – Passenger class (1st, 2nd, 3rd)</li>
          <li><code>Sex</code> – Gender (male/female)</li>
          <li><code>Age</code> – Passenger age</li>
          <li><code>SibSp</code> – Siblings/spouses aboard</li>
          <li><code>Parch</code> – Parents/children aboard</li>
          <li><code>Fare</code> – Ticket fare</li>
          <li><code>Embarked</code> – Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)</li>
        </ul>
      </li>
    </ul>

    <h2>📷 Screenshot</h2>
    <p>A live prediction UI created using Gradio (Add your screenshot here)</p>

    <h2>📌 Tags</h2>
    <div>
      <span class="tag">Machine Learning</span>
      <span class="tag">Maritime Safety</span>
      <span class="tag">Random Forest</span>
      <span class="tag">Python</span>
      <span class="tag">Gradio</span>
      <span class="tag">Disaster Response</span>
    </div>
  </div>
</body>
</html>

