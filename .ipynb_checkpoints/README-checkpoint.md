![RRT](https://images.squarespace-cdn.com/content/v1/5dcdbfbd11d2b74e8b2be4f3/1574102100539-K197GZ80D5B7AVLP4H83/Rapid+Response+Team.jpg?format=1500w) 
# RRT Data Analyses

### Contents:
- [Problem Statement](#Problem-Statement)
- [Background](#Background)
- [Datasets](#Datasets) 
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

### Problem Statement
To conduct data analyses on the total number of RRT activations based on fiscal year 2019 - 2020 (April 2019 - March 2021).

---

### Background
Failures in planning and communication, and failure to recognize when a patient's condition is deteriorating, can lead to failure to rescue and become a key contributor to in-hospital mortality. If identified in a timely fashion, unnecessary deaths can often be prevented. The [Rapid Response Team (RRT)](https://www.ihi.org/Topics/RapidResponseTeams/Pages/default.aspx#:~:text=The%20Rapid%20Response%20Team%20%E2%80%94%20known,(or%20wherever%20it's%20needed).) — known by some as the Medical Emergency Team — is a team of clinicians who bring critical care expertise to the bedside. Simply put, the purpose of the Rapid Response Team is to bring critical care expertise to the patient bedside (or wherever it’s needed).

---

### Datasets
Below are the two given documents used in this data analyses:
- `SICU and MICU Triage Notes.csv`
- `Outcome of Patient.csv`

The above documents have been merged into one and saved as `masterfile.csv`.

---

### Conclusions and Recommendations
**1. Total Number of RRT Activations by Month**
- There is a somewhat similar trend in the total number of RRT activations across the two fiscal years.
- There is a general increasing trend in the first quarter, followed by smaller fluctuations in the second and third quarters, then a decreasing trend in the last quarter of the fiscal year.
- The peaks in the number of RRT activations are in June/July and December/January periods. These coincide with the main school holiday and festive periods in Singapore. Some patients might face more stress during such [festive periods](https://hbr.org/2018/12/holidays-can-be-stressful-they-dont-have-to-stress-out-your-team) resulting in incidences of serious adverse events and RRT activations. Furthermore, there might be a crunch in the hospital manpower, resulting in [patient deterioration not being recognized and responded to in a timely manner](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5221430/) and subsequent RRT activations.

**2. Total Number of RRT Activations by Teams and Month**
- There are generally more RRT activations by SMART team as compared to HERO team. As such, it contributes to the total activations to a larger extent.
- The fluctuations in RRT activations are greater for SMART team as compared to HERO team, with the range in the number of activations by SMART team at 82 and that of HERO team at 28.
- There is a somewhat similar trend in the total number of RRT activations across the two fiscal years by SMART team while that by HERO team is more erratic. As such, the conditions of the patients under the HERO team might be more unstable or the team might have [more reluctance in RRT activations](http://www.smj.org.sg/sites/default/files/SMJ-61-184.pdf) and require more training in it.

**3. Total Number of RRT Activations by Time**
- There are more RRT activations during non-office hours (56.9%) than office hours (43.1%). Below are a few plausible reasons:
  - Non-office hours are proportionally longer than office hours in a day.
  - There is less manpower in the hospital during non-office hours, resulting in patient deterioration not being recognized and responded to in a timely manner and subsequent RRT activations.
  
**4. Total Number of RRT Activations by Disposition**
- Most of the disposition of patients after being seen by either the SMART team or HERO team is to the ICA (38.0%), followed by GW (32.2%), ICU (24.5%) and HDU (5.2%).
- There are seven subgroups under ICA while there is only one subgroup under GW, so the subgroup of GW is already a big subgroup by itself.
- More training might have to be provided in terms of early detection of deterioration of health conditions linked to ICA and GW cases to lower the related RRT activations.

**5. Total Number of RRT Activations by Outcome**
- The top three outcomes from RRT activations are follow-up at clinic (48.5%), followed by death (30.9%) and residential stepdown (10.8%).
- As such, measures have to be put in place to ensure proper handover to subsequent clinics and specialists so that patients are well-taken care of and prevent duplication of efforts.
- Since death constitute to a fairly large proportion of the outcomes (30.9%), more training have to be conducted to improve the effectiveness of the RRT activations and efficency of early detection in deterioration of health conditions.
- Similarly, measures have to be put in place in ensure proper handover to residential stepdown facilities so that patients' conditions do not worsen.