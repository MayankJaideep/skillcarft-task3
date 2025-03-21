# Bank Marketing Decision Tree Classifier

This project uses a Decision Tree Classifier to analyze the **Bank Marketing Dataset** and predict whether a customer will subscribe to a term deposit based on various demographic and behavioral features.

## 📂 Dataset
The dataset (`bank.csv`) contains customer information such as:
- **Demographic Features**: `age`, `marital`, `education`, `job`
- **Behavioral Features**: `housing`, `loan`, `contact`, `month`, `campaign`, `previous`, `poutcome`
- **Target Variable**: `y` (whether the customer subscribed: `yes` or `no`)

## 📌 Dependencies
Ensure you have Python installed along with the following libraries:

```bash
pip install pandas scikit-learn matplotlib
```

## 🚀 Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/bank-marketing-decision-tree.git
   cd bank-marketing-decision-tree
   ```
2. **Run the script:**
   ```bash
   python script.py
   ```

## 🛠 Features Implemented
- Data preprocessing (One-Hot Encoding, Label Mapping)
- Splitting data into training & testing sets
- Training a Decision Tree Classifier (max depth = 5)
- Model evaluation using Accuracy, Classification Report, and Confusion Matrix
- Visualizing the Decision Tree

## 📊 Output Example
- **Accuracy Score**
- **Confusion Matrix**
- **Decision Tree Visualization** (Plotted using `plot_tree()`)

## 📜 License
This project is open-source and available under the **MIT License**.

## 🤝 Contributing
Feel free to fork the repo and submit a pull request with improvements!

## 📧 Contact
For questions or suggestions, reach out via GitHub issues.

---
Happy Coding! 🚀

