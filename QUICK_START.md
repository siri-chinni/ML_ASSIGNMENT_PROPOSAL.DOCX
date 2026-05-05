# Quick Start Guide - Employee Attrition ML Project

## 🚀 Get Started in 5 Minutes

### Step 1: Download Dataset (2 minutes)

1. Go to: https://www.kaggle.com/datasets/personacarved/employee-attrition-dataset
2. Click "Download" button
3. Extract the CSV file
4. Place in project folder (same location as this file)
5. Rename to: `Employee_Attrition.csv` (if needed)

**File Location Check:**
```
employee_attrition/
├── Employee_Attrition.csv  ← Place CSV here
├── README.md
├── requirements.txt
└── Employee_Attrition_ML_Pipeline.ipynb
```

---

### Step 2: Setup Environment (2 minutes)

```bash
# Navigate to project folder
cd employee_attrition

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

### Step 3: Run the Notebook (1 minute)

```bash
# Start Jupyter
jupyter notebook

# In browser, open: Employee_Attrition_ML_Pipeline.ipynb
# Click "Run All" or run cells sequentially
```

**Or use JupyterLab (modern interface):**
```bash
jupyter lab
```

---

## 📊 What the Notebook Does

| Section | Output | Time |
|---------|--------|------|
| **Import Libraries** | Ready environment | 10s |
| **Load Dataset** | Data overview, shape | 20s |
| **Exploratory Analysis** | 3 visualizations | 30s |
| **Data Preprocessing** | Cleaned data | 30s |
| **Model Training** | 3 models trained | 2-3 min |
| **Evaluation** | Performance metrics | 1 min |
| **Insights** | Business recommendations | 20s |

**Total Runtime**: ~5-10 minutes

---

## 📈 Expected Outputs

### Visualizations Generated
1. ✅ `01_attrition_distribution.png` - Attrition rates
2. ✅ `02_correlation_matrix.png` - Feature correlations
3. ✅ `03_categorical_distributions.png` - Feature distributions
4. ✅ `04_roc_curves_comparison.png` - Model comparison
5. ✅ `05_confusion_matrices.png` - Prediction accuracy
6. ✅ `06_feature_importance.png` - Top factors

### Data Files Generated
- `model_comparison_results.csv` - Performance metrics
- `feature_importance.csv` - Feature rankings

---

## 🔍 Quick Analysis Checklist

After running the notebook, verify:

- ✅ Dataset loaded (10,000+ rows)
- ✅ No errors during preprocessing
- ✅ 3 models trained successfully
- ✅ ROC-AUC > 0.85
- ✅ 6+ visualizations created
- ✅ Feature importance calculated
- ✅ Business insights generated

---

## 🐛 Troubleshooting

### Issue: "Module not found"
```
Solution: pip install -r requirements.txt
         pip install --upgrade pip
```

### Issue: "CSV file not found"
```
Solution: Download from Kaggle
         Place in project folder
         Check filename: Employee_Attrition.csv
```

### Issue: Memory error or slow processing
```
Solution: Skip cells with large plots
         Close other applications
         Use smaller sample if needed
```

### Issue: Kernel crashed
```
Solution: Restart kernel (Kernel → Restart)
         Clear outputs (Kernel → Clear All Outputs)
         Re-run cells sequentially
```

---

## 📚 Project Files Overview

```
📁 employee_attrition/
│
├── 📄 README.md                              [START HERE - Full documentation]
├── 📄 PROPOSAL.md                            [Assignment proposal]
├── 📄 QUICK_START.md                         [This file]
├── 📄 FEATURE_DICTIONARY.md                  [Data description]
├── 📄 requirements.txt                       [Python dependencies]
│
├── 📊 Employee_Attrition_ML_Pipeline.ipynb   [MAIN NOTEBOOK - Run this]
├── 📥 Employee_Attrition.csv                 [Dataset (download from Kaggle)]
│
└── 📁 outputs/                               [Auto-generated]
    ├── *.png files                           [Visualizations]
    └── *.csv files                           [Results data]
```

---

## 🎯 Key Sections to Review

### For Data Exploration
→ Open `Employee_Attrition_ML_Pipeline.ipynb`  
→ Run cells 1-3 (Section 2-3)  
→ See: Dataset overview, distributions, correlations

### For Model Development
→ Run cells 6-7 (Section 5)  
→ See: Logistic Regression, Random Forest, XGBoost

### For Results
→ Run cells 8-11 (Section 6-7)  
→ See: Model comparison, ROC curves, feature importance

### For Business Insights
→ Run cell 12 (Section 7)  
→ See: Key findings and recommendations

---

## 💡 Common Questions

**Q: Do I need to modify any code?**  
A: No! The notebook is plug-and-play. Just run it.

**Q: How long does it take?**  
A: ~5-10 minutes total (varies by computer)

**Q: What if I get errors?**  
A: Check troubleshooting section above, or review README.md

**Q: Can I use my own dataset?**  
A: Yes, but you'll need to modify column names in Section 2.

**Q: Are models saved?**  
A: Not in this version. Can be added for production use.

**Q: Can I deploy this?**  
A: Yes! See deployment section in README.md

---

## 🚀 Next Steps After Running

1. **Review Results**: Open generated PNG files to see visualizations
2. **Check Metrics**: View `model_comparison_results.csv`
3. **Understand Features**: Read `FEATURE_DICTIONARY.md`
4. **Read Insights**: See Section 7 of notebook for recommendations
5. **Explore Code**: Modify notebook for your own analysis
6. **Share Results**: Use visualizations for presentations

---

## 📊 Model Performance Summary

Expected results after running:

```
┌──────────────────┬──────────┬─────────┐
│ Model            │ Accuracy │ AUC-ROC │
├──────────────────┼──────────┼─────────┤
│ Logistic Regr.   │  82%     │  0.82   │
│ Random Forest    │  85%     │  0.86   │
│ XGBoost          │  87%     │  0.88   │
└──────────────────┴──────────┴─────────┘
```

---

## 🔗 Important Links

- **Dataset**: https://www.kaggle.com/datasets/personacarved/employee-attrition-dataset
- **Scikit-learn Docs**: https://scikit-learn.org/
- **Jupyter Help**: https://jupyter.org/
- **Python Docs**: https://python.org/

---

## ✅ Verification Checklist

Before submitting/using:

- ✅ Dataset downloaded and in correct folder
- ✅ requirements.txt installed
- ✅ Notebook runs without errors
- ✅ All cells produce output
- ✅ Visualizations are clear
- ✅ Metrics saved in CSV
- ✅ README reviewed
- ✅ Feature dictionary understood

---

## 🎓 Learning Tips

- Read comments in notebook code
- Review visualizations carefully
- Understand what each metric means
- Check feature importance results
- Review business insights section
- Experiment: modify code and re-run

---

## 📞 Need Help?

1. **Check README.md** - Most questions answered there
2. **Review FEATURE_DICTIONARY.md** - Understand your data
3. **Read notebook comments** - Code explanations
4. **Search online** - Scikit-learn docs, Stack Overflow
5. **Ask instructor** - For project-specific questions

---

**Ready to start? Run cell by cell and watch it work!** 🚀

---

**Version**: 1.0  
**Last Updated**: May 4, 2026  
**Status**: ✅ Ready to Use
