
# 📊 Dataset Analyzer

Dataset Analyzer is a powerful web-based tool that simplifies exploratory data analysis (EDA) for CSV and JSON datasets. Upload your data, visualize distributions, detect anomalies, and download summary reports — all in one intuitive dashboard.

---

## 🚀 Features

- ✅ Upload CSV or JSON datasets
- 📈 Interactive charts: histograms, scatter plots, box plots, correlation heatmaps
- 🔍 Automatic missing value detection & summary statistics
- ⚡ Fast in-browser analysis supported by Web Workers
- 📄 Exportable summary report (PDF format)

---

## 🧰 Tech Stack

- **Frontend**: React.js, Chart.js (or D3.js)
- **Backend**: Node.js, Express.js (optional API layer)
- **Data Processing**: Web Workers
- **Utilities**: Axios, FileSaver.js, react-dropzone

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/rupeshkumar18123/Dataset_analyzer.git
cd Dataset_analyzer
````

### 2. Install dependencies

```bash
npm install
```

*(Or, if there is a `backend` folder:)*

```bash
cd backend
npm install
cd ../frontend
npm install
```

---

## ▶️ Running the App

Start the development server:

```bash
npm start
```

* If there’s a combined setup, the app should open automatically at `http://localhost:3000`.
* If separate: run both `npm start` in frontend and backend directories.

---

## ⚙️ Usage

1. Navigate to the web app.
2. Drag-and-drop or select your dataset.
3. Choose charts and analysis options.
4. View interactive visualizations.
5. Export summary PDF report via “Download Report” button.

---

## ⚠️ Requirements

* Node.js ≥ 12
* Modern browser (Chrome/Firefox/Edge/Safari)

---

## 📸 Screenshots

*(Insert screenshots of data upload, chart views, and export actions here.)*

---

## 💡 Future Enhancements

* 📑 Support for XLSX and SQL data
* 🗃️ Save/load analysis sessions
* 📊 Advanced EDA: clustering, PCA
* 🔧 Custom visualization palette & themes

---

## 🤝 Contributing

We welcome contributions!

1. Fork the repo
2. Create a branch: `feature/your-feature-name`
3. Commit your changes
4. Push to GitHub and open a PR

Please follow existing code style and write clear commit messages.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

Built with passion by [Rupesh Kumar](https://github.com/rupeshkumar18123).
Feel free to connect and share feedback!

```

