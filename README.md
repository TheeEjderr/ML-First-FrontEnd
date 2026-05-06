# Sleep Quality Prediction - Web Interface

A web-based machine learning application that predicts sleep quality using **Linear Regression** and **Python scikit-learn**. This frontend provides an interactive interface to input sleep-related parameters and receive predictions.

## 🌐 Live Demo

Visit the live website: [https://theeejderr.github.io/ML-First-FrontEnd/](https://theeejderr.github.io/ML-First-FrontEnd/)

## 📋 Description

This application demonstrates the practical implementation of machine learning in web development. It uses a Linear Regression model trained on sleep quality data to predict sleep quality scores based on user input. The frontend provides an intuitive user interface where users can enter parameters such as:

- Sleep duration
- Exercise frequency
- Caffeine intake
- Stress levels
- Screen time before bed
- Bedroom temperature
- And other relevant sleep factors

The model processes these inputs and returns a predicted sleep quality score.

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend ML Model:** Python, scikit-learn (Linear Regression)
- **Data Processing:** pandas, NumPy
- **Deployment:** GitHub Pages (Frontend), Flask/FastAPI (Backend API)

## 📂 Project Structure

```
ML-First-FrontEnd/
├── README.md
├── index.html          # Main application interface
├── css/                # Styling files
├── js/                 # Client-side JavaScript logic
├── assets/             # Images, icons, and resources
└── data/               # Sample datasets (if applicable)
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3.7+ (for running the backend ML model locally)
- pip (Python package manager)

### Installation

#### Frontend Setup

1. Clone the repository:
```bash
git clone https://github.com/TheeEjderr/ML-First-FrontEnd.git
cd ML-First-FrontEnd
```

2. Open `index.html` in your web browser to access the application

#### Backend ML Model Setup (Optional - for local development)

1. Install required Python packages:
```bash
pip install scikit-learn pandas numpy flask
```

2. Navigate to the backend directory:
```bash
cd backend
```

3. Run the Flask API server:
```bash
python app.py
```

The API will be available at `http://localhost:5000`

### Deployment

This project is deployed on GitHub Pages. Any changes pushed to the `main` branch will automatically update the live site.

## 📖 Usage

1. **Open the Application:** Navigate to the live demo link or open `index.html` locally
2. **Enter Sleep Parameters:** Fill in the form with your sleep-related data
3. **Submit:** Click the "Predict" button
4. **View Results:** The application will display your predicted sleep quality score and personalized recommendations

### Example Input
- Sleep Duration: 7.5 hours
- Exercise Frequency: 4 days/week
- Caffeine Intake: 2 cups/day
- Stress Level: 5/10
- Screen Time: 1.5 hours before bed
- Room Temperature: 68°F

## 🤖 Machine Learning Model

### Algorithm: Linear Regression

**Why Linear Regression?**
- Simple and interpretable model
- Fast predictions
- Effective for continuous output (sleep quality scores)
- Provides clear feature importance

**Training Data:**
- Features: Sleep-related parameters
- Target: Sleep quality score (0-100)
- Method: scikit-learn's LinearRegression

**Model Accuracy:** [Update with actual metrics - R² score, RMSE, etc.]

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

MIT License - feel free to use this project for your own purposes

## 👤 Author

**TheeEjderr**
- GitHub: [@TheeEjderr](https://github.com/TheeEjderr)

## 📧 Contact & Support

For questions or issues, please open an issue on the GitHub repository or contact the project maintainer.

## 📚 References

- [scikit-learn Linear Regression Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- [Sleep Quality Research](https://en.wikipedia.org/wiki/Sleep_quality)
- [Machine Learning Best Practices](https://scikit-learn.org/stable/)

## 🔗 Related Projects

- [Sleep Quality Dataset](https://www.kaggle.com/)
- [ML Model Repository](https://github.com/TheeEjderr/)

---

**Note:** This project demonstrates the integration of machine learning models with web interfaces. The model is for educational purposes and should not be used as a replacement for professional medical advice.
