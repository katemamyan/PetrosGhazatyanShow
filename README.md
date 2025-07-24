# **Who’s Petros Ghazaryan’s Favorite Guest?**
### **Statistical Breakdown**

## **Project Overview**
This project analyzes the guests on **Petros Ghazaryan’s show** to explore who the most frequent guests are and how the **ruling party** uses **Public TV** as a platform for discussions. I aimed to visualize and analyze the frequency of appearances of gests, and the overall influence of the ruling party’s members in the show.

## **Short Description**
The goal was to identify who the most frequent guests of Petros Ghazaryan's show are, with a special focus on the dominance of the **Civil Contract** ruling party in terms of airtime and guest appearances. The project involves scraping the show's archive, pulling YouTube data for views and interview durations, and performing data analysis to generate insights.

## **Key Findings**
- My hypothesis that the majority of the guests are from the **Civil Contract** ruling party was supported by the data. However, the proportion of time spent on ruling party members (52.7%) was less than I expected.

## **Data Collection Process** [You can find code here](https://github.com/katemamyan/LEDE_PROGRAM/tree/main/project_01)
### **1. Scraping (1-2 days)**
- I scraped the list of Petros Ghazaryan's interviews, including links, titles, and YouTube links, from the **Public TV archive**.
  
### **2. YouTube API (1 day)**
- Using **ChatGPT**, I fetched information about the view counts and durations of the interviews through the **YouTube API**.

## **Data Analysis Process**
### **1. Data Cleaning (1-2 days)**
- The data cleaning process was challenging because the archive wasn’t well-organized. There were many videos unrelated to Petros Ghazaryan’s show, requiring manual filtering (which I hate, but I did it anyway because I’m a bit paranoid about data accuracy). 
- I used **regular expressions** to standardize titles and fix inconsistencies (not the most optimal solution, but it worked).

### **2. Analysis (4-5 days)**
- Some titles were inconsistent: for example, some were formatted as **"Petros Ghazaryan’s interview with NAME SURNAME"**, others as **"Interview with NAME SURNAME"**, and others just as **"Interview with the Prime Minister"**.
- I used **pivot tables** and **groupby** functions in **Pandas** to analyze the data, and then merged the results with YouTube API data and exported it to **Google Sheets** for visualization preparation.

## **Design, Visualization, and Web Page Creation (5-7 days)**
- I built the website from scratch, created the design, and integrated the visualizations. It was a learning curve for me since I usually work with tools like WordPress. But this project helped me understand how **HTML, CSS**, and **JavaScript** work together. I also learned a lot about **responsive design**, especially the importance of ensuring the page looks good on both desktop and mobile devices.

## **Skills and Tools Used**
### **Programming and Libraries:**
- **Python**: Beautiful Soup, Requests, Pandas, regex, YouTube API, and a library to crop guest faces into circles for data visualization.
- **Google Sheets**: For preparing data for visualization.
- **DataWrapper, Flourish, Figma**: For creating data visualizations.
- **HTML, CSS, JavaScript**: For building the webpage. This was my first time working on a project from scratch.

### **ChatGPT**: I used it for coding assistance and explanations whenever I got stuck, especially with complex code and logic.

## **What I Learned**
This project was a huge learning experience for me. I gained skills in:
- **Web development basics** (building the page from scratch, making it responsive).
- **Data analysis** (scraping, cleaning, analyzing, and visualizing data).
- **Visualization tools** (working with DataWrapper, Flourish, Figma).

## **Challenges and Limitations**
### **Things I Couldn’t Achieve or Wanted to Do**
- **Bubble Chart as Interactive SVG**: I wanted to include an interactive bubble chart in SVG format, but the **Figma to HTML plugin** generated poor-quality code. So, I ended up using a **static image** for the bubble chart.
  
- **Broader Data Set**: If I had more time, I would have analyzed data for **all guests**, not just those with 5+ appearances.
  
- **AI Classification**: I attempted AI classification to categorize guests by political party affiliation, but the results were inaccurate, so I manually classified them with the help of journalist friends.

- **Transcriptions for Text Analysis**: Ideally, I would have loved to get **transcriptions** of interviews and perform **text analysis** to gain deeper insights, but this wasn't possible within the time frame.

## **Conclusion**
This project was both **challenging** and **rewarding**. It allowed me to explore various techniques and tools and deepened my understanding of **data collection, analysis, visualization**, and **web development**. I’m thankful to the **Lede Program** and my instructors for the inspiration and support. I’m excited to continue learning and improving!

---

### **Links**:
- [GitHub Repository](https://github.com/katemamyan/LEDE_PROGRAM)
- [Telegram Channel](https://t.me/datajourno)

