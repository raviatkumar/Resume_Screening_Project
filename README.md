# **Project Title : Resume Screening**

## **Problem Statement:**

In the competitive job market, companies are inundated with a massive influx of resumes for each job opening, necessitating an efficient and effective method for talent acquisition. The challenge is particularly pronounced for labor-intensive businesses experiencing growth and high attrition rates. The IT industry, amid rapid expansion, faces a shortage of skilled professionals. To address the daunting task of selecting the most suitable candidates from a plethora of resumes, companies turn to machine learning algorithms for automated Resume Screening. Large organizations, constrained by time, seek innovative solutions to sift through resumes swiftly, leveraging technology to identify and prioritize candidates with the requisite technical skills and business domain expertise. This process aims to streamline the hiring workflow, ensuring that companies secure the right talent for their projects and customer needs.

## **Conclusion:**

1. **MultinomialNB:**
   - **Accuracy:** 96%
   - **Highlights:**
     - High precision and recall for most classes.
     - Some classes with lower recall may benefit from further model optimization.
   - **Recommendation:**
     - Overall, the model performs well, but there is room for improvement in certain classes with lower recall.

2. **GaussianNB:**
   - **Accuracy:** 99%
   - **Highlights:**
     - Exceptional performance with high precision, recall, and F1-score for all classes.
     - Robust handling of the dataset, showcasing consistent results across diverse job categories.
   - **Recommendation:**
     - The GaussianNB model demonstrates outstanding overall performance, making it a preferable choice for resume screening in this context.

**Comparison:**
- Both models exhibit commendable accuracy, but GaussianNB stands out with near-perfect results.
- GaussianNB is well-suited for scenarios where data distribution assumptions of the MultinomialNB may not hold.
- Further analysis should focus on refining the MultinomialNB model to enhance its performance on specific job categories with lower recall.

In summary, while MultinomialNB performs reasonably well, GaussianNB emerges as the superior choice for the resume screening task in this context, showcasing exceptional accuracy and robustness across diverse job categories.
