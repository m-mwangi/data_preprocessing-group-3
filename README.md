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
- **merged_dataset.csv** - Merged dataset  
- **final_customer_data_group3.csv** – Merged dataset with Feature Engineering 

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

### Data Cleaning & Augmentation
- Handle missing values  
- Apply data augmentation techniques  

### Merging Datasets
- Use `id_mapping.csv` to link datasets  
- Merge `customer_transactions_augmented.csv` with `customer_social_profiles.csv`  

### Feature Engineering & Transformation
- Create new features  
- Perform data transformations  

### Data Consistency & Quality Checks
- Check for duplicates  
- Validate data consistency  

## **Export Final Processed Data**
Save the final datasets after preprocessing:

- `customer_transactions_augmented.csv`  
- `final_customer_data_[groupNumber].csv`  
- `final_dataset_ready_[groupNumber].csv`  

## **Demo Video**
https://youtu.be/q8NY7bDX2IU

## **Summary Report**
https://github.com/m-mwangi/data_preprocessing-group-3/blob/be101d18f7492ff5f509ded3a30d3962bf964159/Peer_Group3_Data%20Preprocessing_Summary%20Report.pdf


