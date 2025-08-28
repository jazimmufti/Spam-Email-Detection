<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h1>Spam Email Detection using Machine Learning</h1>
    <h2>Overview</h2>
    <p>This project implements a Spam Email Detection system using machine learning models. 
    The goal is to classify emails as <strong>Spam</strong> or <strong>Ham (Not Spam)</strong> 
    based on their content. Spam detection is critical for email service providers to reduce 
    malicious activity, phishing, and junk mail, ensuring a safer user experience. 
    In this project, text data is transformed into numerical features using 
    <strong>TF-IDF (Term Frequency–Inverse Document Frequency)</strong> before training models.</p>
    <h2>Dataset</h2>
    <p>The dataset contains labeled emails, where each message is classified as spam or ham.</p>
    <ul>
        <li>Source: Enron / SMS Spam Collection dataset (or your dataset)</li>
        <li>Total emails: ~5,000 (replace with actual number)</li>
        <li>Spam emails: ~800</li>
        <li>Ham emails: ~4,200</li>
        <li>Text-based dataset with target labels</li>
    </ul>
    <h2>Features</h2>
    <ul>
        <li><strong>Message</strong> – The raw email or SMS text</li>
        <li><strong>Label</strong> – Spam (1) or Ham (0)</li>
        <li><strong>Engineered Features</strong> – TF-IDF.</li>
    </ul>
    <h2>Methodology</h2>
    <h3>Data Preprocessing</h3>
    <ul>
        <li>Lowercasing and cleaning text</li>
        <li>Removing stopwords and punctuation</li>
        <li>Vectorization using TF-IDF(Term Frequency–Inverse Document Frequency)</li>
    </ul>
    <h3>Evaluation</h3>
    <p>Models are evaluated using the following metrics:</p>
    <ul>
        <li>Accuracy</li>
        <li>Precision</li>
        <li>Recall</li>
        <li>F1-score</li>
        <li>Confusion Matrix</li>
    </ul>
    <h2>Results</h2>
    <p>The best-performing model i.e, Logistic Regression achieved a tremendous accuracy of 97% alongside high
    recall and precision, effectively detecting spam messages while minimizing false positives.</p>
    <h2>Conclusion</h2>
    <p>This project demonstrates the application of machine learning for spam detection and 
    highlights the importance of text preprocessing, <strong>TF-IDF feature extraction</strong>, 
    and model selection for NLP tasks.</p>
    <h2>Future Work</h2>
    <ul>
        <li>Experiment with deep learning models (LSTM, BERT)</li>
        <li>Deploy as a web API or email filter</li>
        <li>Real-time spam detection</li>
    </ul>
    <h2>References</h2>
    <ul>
        <li>Dataset: <a href="https://archive.ics.uci.edu/ml/datasets/sms+spam+collection" target="_blank">UCI SMS Spam Dataset</a></li>
        <li>Scikit-learn Documentation: <a href="https://scikit-learn.org/stable/" target="_blank">Scikit-learn Documentation</a></li>
    </ul>
</body>
</html>
