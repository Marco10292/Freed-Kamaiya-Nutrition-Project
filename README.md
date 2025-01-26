# Freed-Kamaiya-Nutrition-Project
Portfolio project on Freed-Kamaiya lactating women, with data taken directly on the field trough interviews, in *Bardiya District*, Nepal.

The Mukta-Kamaiya, meaning freed-Kamaiya, are a marginalized community found in the *western Terai region*.
Their status is shaped by both caste system and historical bonded labour practices present in Nepal, which illustration enables a more comprehensive analysis.


## 📚 About Data

The data has been taken by the author of [this Master's thesis](https://github.com/Marco10292/Freed-Kamaiya-Nutrition-Project/blob/main/Master's%20thesis%3B%20food%20intake%20adequacy%20MK%20communities.pdf), which approved the use of the data.

The interviewed subjects are *pregnant and lactating women both from the Mukta-Kamaiya community* (freed bonded-labourers) and pregnant and lactating women not from that group: the aim of the research was to assess their nutrient adequacy and to find relevant differences between these two backgrounds.

Although the sample size is relatively small, the dataset includes high-quality quantitative variables that provide valuable insights.

The dataset comprises 52 fields, but this analysis will focus on the *first 18 variables* visible in the Excel file: the details of these variables are provided in the comments and will be further elaborated upon throughout the analysis.

## 💡 Excel

📍 [File:](https://github.com/Marco10292/Freed-Kamaiya-Nutrition-Project/blob/main/Freed-Kamaiya%20nutrition%20project.xlsx)
- On **Excel**, I first outlined the composition of the variables and provided a brief description, then I indexed each woman's name.
I choose **GLOBADEQUACY** (a variable that indicates how much all nutrients' intake are covered, where 100 = perfect coverage ) and **MDDW** (Minimum Dietary Diversity of Women score, from 0 to 10) as *'target variables'*. 
They indicate the general dietary well-being of the women.
- I applied a **general descriptive statistical analysis** to both variables, along with calculating the correlation indices between them.
- Another key variable is **MK**, which indicates the status of Mukta-Kamaiya (associated with a potentially greater risk of inadequate food intake, represented by a value of 1) and non-Mukta-Kamaiya (represented by a value of 0). This variable enables interesting analyses and hypotheses. I found that individuals with MK = 1 are undoubtedly worse off than those with MK = 0.
- Finally, I located outliers for both variable using the **Interquartile Range (IQR)**, which proved to be marginals.

## ⚙️ Python analysis

📍 [File:](https://github.com/Marco10292/Freed-Kamaiya-Nutrition-Project/blob/main/Freed_Kamaiya_nutrition_project.ipynb)
-  I execute a deeper analysis with Python, where I attempt **clustering analysis** and I expose in details the various results.
-  Are wealth and education influencing nutrient adequacy?  

## 📊 Visualization

- This simple Dashboard is interactive and wants to show how many women assumed a sufficient quantity of many different nutrients, such as proteins, sodium or iron.
- Dashboard also shows how many subjects ate a certain food type the day of the interview and which nutrients are lacking the most among them.

**Open the link to visualize and interact with the Tableau Dashboard**

**Tableau:** [Link]()

![image](https://github.com/user-attachments/assets/7a88afd7-f38b-4bb1-a7c0-b4336dfef93a)
