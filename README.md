# Usability Test: Systematic Review App

## Complete 30-Minute Test Protocol

**Topic:** Mobile Apps and User Experience  
**Total Time:** 40 minutes + 10 minutes survey  
**Participants:** 5 students (no prior systematic review experience needed)

## Background

Researchers have a research question and must find relevant articles. They export references from multiple online databases in Bib format and remove duplicates. They then review the articles in two stages: in the first stage, they examine the title and abstract, and for the included article, they move on to the next stage, which examines
the full-text content. Next, the included article moves on to data extraction, which is similar to a spreadsheet in which researchers create questions in form of columns and answer them. They can also perform qualitative analysis, similar to HCI, highlighting relevant words in codes and creating themes. Finally, charts help visualise the extracted data and identify connections.

## Task 1: Setup & Import (3 minutes)

### Instructions for Participant:

**1.1 Create Account (1 min)**

- Click "Sign Up"
- Fill in basic information. Use fake credentials.
- Log in

**1.2 Create Review (1 min)**

- Create new review
- Title: **"Mobile Apps and User Experience"**
- Descrition: **"What factors affect user satisfaction with mobile apps?"**

**1.3 Import References (1 min)**

- Upload the BibTeX file from USB drive: `mobile_ux_dataset.bib`
- Wait for import to complete
- **Verify:** You should see 20 papers

---

## Task 2: Handle Duplicates (2 minutes)

### Instructions:

**2.1 Run Duplicate Detection**

- Click "Detect Duplicates" button

**2.2 Resolve 2 Duplicate Pairs (2 min)**

- Click "Continue Resolving" button
- For each pair shown, decide the version that has more information and click **Keep Left** or **Keep Right**

**Expected:** 2 duplicate pairs to resolve

---

## Task 3: Screening (8 minutes)

### Simple Screening Criteria (printed card given to participant):

```
┌─────────────────────────────────────┐
│  INCLUDE if title/abstract has:     │
│  ✓ user, experience, satisfaction   │
│  ✓ usability, interface, design     │
├─────────────────────────────────────┤
│  EXCLUDE if title/abstract has:     │
│  ✗ battery, energy, security        │
│  ✗ network, protocol, 5G            │
│  ✗ framework, compiler, debugging   │
├─────────────────────────────────────┤
│  MAYBE if you're unsure!            │
└─────────────────────────────────────┘
```

### Part A: Use Keyword Filters (3 min)

**Test keyword filter:**

1. Create keyword for include "**User**"
2. Filter references by ticking the User checkbox
3. Create and Apply Label "**User**" to all of them
4. Mark all of them as included

## Task 4: Full-Text Review (2 minutes)

1. Click add articles and import included articles from screening
1. Search in the search bar "Understanding What Makes Mobile Apps Frustrating: A User Study"
1. Click "**Upload PDF**" button
1. Upload PDFs from (`test_pdfs/` folder)
1. Verify file status changes
1. Mark it as included
1. Do all the previouse steps for "Factors Influencing User Satisfaction with Mobile Shopping Applications"

## Task 5: Data Extraction (5 minutes)

### Extraction Data Cheat Sheet (provided):

**Extract from 2 papers only** (to save time):

Create questions:

- Publication Year with type number
- Publication Type with type select and options: Conference Paper or Journal Articles
- User Study Size: number
- Design Recommendations: Yes/No

#### Paper 1: Smith 2020 - User Frustration

```
Publication Year: 2020
Publication Type: Conference Paper
User Study Size: 800
Design Recommendations: Yes
```

#### Paper 2: Chen 2019 - Shopping Satisfaction

```
Publication Year: 2019
Publication Type: Journal Article
User Study Size: 50
Design Recommendations: Yes
```

---

### Instructions:

34. Go to "**Data Extraction**" tab
35. Select **Smith 2020** paper
36. Click View PDF
37. Open the extraction sidebar on the right
38. Fill in the form using cheat sheet above (2 min)
39. Mark as completed and close the PDF
40. Select **Chen 2019** paper
41. Fill the rows using cheat sheet above (2 min)
42. Mark as completed

---

## Task 6: Coding & Theming (5 minutes)

### Instructions:

**Open the special PDF:** `smith2020_FOR_CODING_TASK.pdf`

This PDF has 5 text sections marked with `[CODE 1]` through `[CODE 5]`.

---

### Part A: Create Codes (2 min)

**Find and highlight the 5 marked sections:**

---

### Part B: Create Themes (3 min)

34. Go to "**Coding & Theming**" tab

**Organize codes into themes:**

43. Create sub-theme: **"Technical Issues"**
44. **Drag** "Slow Performance" into it
45. **Drag** "Poor Navigation" into it

46. Create sub-theme: **"Content Issues"**
47. **Drag** "Annoying Ads" into it

48. Create sub-theme: **"User Behavior"**
49. **Drag** "Low Reteunsion" into it

50. Create main theme: **"App Frustrations"**
51. **Drag all sub-themes** under main theme

**Expected hierarchy:**

```
📁 App Frustrations
   ├─ Technical Issues
   │   ├─ Slow Performance
   │   └─ Poor Navigation
   └─ Content Issues
       └─ Annoying Ads
   └─ User Behaviour
       └─ Low Retention
```

---

## Task 7: Generate Charts (3 minutes)

### Instructions:

Go to "**Charts**" tab:

---

### Chart 1: Bar Chart (45 sec)

50. Select "**Bar Chart**"
51. Choose field: **"Publication Type"**
52. Wait for chart to generate
53. **Observe:** Conference vs Journal distribution

---

### Chart 2: Timeline (45 sec)

54. Select "**Publication Timeline**"
55. Wait for chart to generate
56. **Observe:** Papers by year (2019, 2020)

---

### Chart 3: Scatter Plot (45 sec)

57. Select "**Scatter Plot**"
58. X-axis: **Publication Year**
59. Y-axis: **User Study Size**
60. Wait for chart to generate
61. **Observe:** Two data points (50 and 800 participants)

---

### Chart 4: Evidence Gap Map (Optional - if time)

62. Select "**Evidence Gap Map**"
63. Rows: **Primary UX Aspect**
64. Columns: **Main Finding Category**
65. Wait for chart to generate

---

### Chart 5: Prisma (Optional - if time)

62. Select "**PRISMA**" in the top tab
63. Wait for chart to generate
64. Can you understand the data? If you scroll down at the bottom and hover on the labels an explanation will appear

---

## Test Complete! (30 minutes elapsed)

---

## Post-Test Survey (10 minutes)

## https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=KVxybjp2UE-B8i4lTwEzyMrJBIjeQMdMnesMZDt4KANUNjVCSkc5OUFKUEZGTldYNlFCRFgyMkNOOC4u
