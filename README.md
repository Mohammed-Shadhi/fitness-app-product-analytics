# Fitness App Product Analytics & Retention Strategy

## 📌 Project Overview
In this case study, I analyzed a dataset of 20,000+ gym members to solve two major product challenges: high onboarding friction and Month-3 user churn. By using Python to analyze demographic trends and cohort behaviors, I transformed raw data into actionable product feature recommendations.

## 🛠️ Tech Stack & Tools
* **Python** (Pandas, Matplotlib, Seaborn)
* **Jupyter Notebooks / Google Colab**
* **Product Strategy & Cohort Analysis**

## 📊 Phase 1: Onboarding Personalization
To reduce the number of questions asked during sign-up, I analyzed the data to build a predictive "Smart Suggestion" engine. 
* **Insight 1:** Workout preferences skew significantly by gender. The data revealed Female users predominantly prefer Strength training, while Male users prefer Cardio. 
* **Insight 2:** The core demographic (Ages 18-39) consists overwhelmingly of beginners. 
* **Action:** Shifted the product roadmap away from complex, advanced metric tracking in favor of beginner-friendly video tutorials and auto-assigned routines based on age and gender.

## 📉 Phase 2: Month-3 Churn Analysis
User retention typically drops off around the 90-day mark. I segmented the users to identify the root causes of churn (boredom, lost motivation, and physical plateaus) and designed specific app features to solve them:

### 🚀 Proposed Product Features
1. **The "Progress Compare" (Fixes Motivation):** Rather than intimidating social leaderboards, I proposed a feature that compares a user's current stats strictly to their "Day 1" metrics, utilizing the sunk-cost fallacy to keep them engaged.
2. **The "Level-Up Shuffler" (Fixes Boredom):** An automated routine swapper that detects when a user has been on the same program for too long and introduces new, higher-tier exercises to gamify progression.
3. **Educational Coaching & Awareness (Fixes Plateaus):** To combat users quitting when their progress naturally slows, I proposed an automated notification system. When the app detects a plateau in the user's data, it triggers targeted educational videos and coaching prompts to reset their expectations and shift their focus to non-scale victories.
4. 3. **Mid-Workout Voice Commands:** Added hands-free logging (e.g., "Hey App, this weight is too heavy") to remove UI friction while users are actively lifting and sweaty. it solves the mid-workout mess
