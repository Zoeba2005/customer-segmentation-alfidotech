# Task 2 — Customer Segmentation Analysis
## Alfido Tech Data Analytics Internship

## Objective
Segment 2,627 customers into meaningful groups for targeted marketing
using KMeans Clustering.

## Method Used
- KMeans Clustering (K=4)
- Elbow Method to find optimal K
- PCA for 2D visualization
- Python: pandas, scikit-learn, matplotlib, seaborn

## Files in This Folder
| File | Description |
|------|-------------|
| customers_segmented.csv | Full dataset with cluster labels |
| segment_profiles.csv | Summary profile of each segment |
| Customer_Segmentation_Report.pdf | Full report with charts & recommendations |

## Customer Segments Found
| Segment | Description | Count |
|---------|-------------|-------|
| 💎 High Value Professionals | Mid-age, married, average spending | 1,030 |
| 👨‍👩‍👧 Family Oriented | Young, large families, low spending | 596 |
| 🌱 Young Starters | Senior, married, average spending | 354 |
| 🏠 Homemakers & Seniors | Educated, experienced, low spending | 647 |

## Key Recommendations
1. Premium Loyalty Program for High Value Professionals
2. Budget-Friendly Campaigns for Family Oriented customers
3. Career & Aspiration Upsell for Homemakers & Seniors

## Tools Used
- Python (scikit-learn, pandas, matplotlib)
- KMeans Clustering
- Reportlab (PDF generation)
