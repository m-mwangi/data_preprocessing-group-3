# **Formative 2 - Data Preprocessing Assignment for Machine Learning Pipeline**  

## **Introduction**  
This project focuses on data preprocessing for a machine learning pipeline. We handle missing values, perform dataset merging using transitive relationships, engineer new features, and ensure data consistency.

### **Objectives**  
- Data Cleaning & Augmentation  
- Dataset Merging using ID Mapping  
- Feature Engineering & Transformation  
- Data Consistency & Quality Checks    

---

## **Dataset Overview**  
The project involves three datasets:  

1. **customer_transactions.csv** - Contains customer transactions and purchase behaviors.  
2. **customer_social_profiles.csv** - Contains customer social media activity and purchase interest scores.  
3. **id_mapping.csv** - Maps legacy customer IDs to new customer IDs.  

### **Generated Datasets**  
- **customer_transactions_augmented.csv** – Processed transaction dataset with augmentation.  
- **final_customer_data_[group3].csv** – Merged dataset with social profiles.  
- **final_dataset_ready_[group3].csv** – Fully processed dataset ready for ML.  

---

## **Installation & Setup**  

### **Requirements**  
Ensure you have the following installed:  
- Python 3.x  
- Jupyter Notebook or Google Colab   

# **How to Run the Notebook**

## **Clone the Repository**
To get started, clone the repository and navigate to the project directory:

```bash
git clone <https://github.com/m-mwangi/data_preprocessing-group-3.git>
cd <data_preprocessing-group-3>
```

## **Run Each Section in Order**

Execute the following sections sequentially to ensure proper data processing:

### **Data Cleaning & Augmentation**
- Handle missing values  
- Apply data augmentation techniques  

### **Merging Datasets**
- Use `id_mapping.csv` to link datasets  
- Merge `customer_transactions_augmented.csv` with `customer_social_profiles.csv`  

### **Feature Engineering & Transformation**
- Create new features  
- Perform data transformations  

### **Data Consistency & Quality Checks**
- Check for duplicates  
- Validate data consistency  

## **Export Final Processed Data**
Save the final datasets after preprocessing:

- `customer_transactions_augmented.csv`  
- `final_customer_data_[groupNumber].csv`  
- `final_dataset_ready_[groupNumber].csv`  

Now your dataset is ready for machine learning! 🚀

