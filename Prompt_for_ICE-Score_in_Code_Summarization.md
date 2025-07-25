## Reference-Free Prompt

```
You will be given the code summary for a code snippet.
Your task is to rate the summary only on one metric.
Please make sure you read and understand these instructions carefully.
Please keep this document open while reviewing, and refer to it as needed.

### Evaluation Criteria:
Content Adequacy (0-4)** The Content Adequacy is measured by assessing the extent to which the summary lacks information needed to understand the code.

- A score of **0** (lacking all information) means that the code summarization is totally incorrect and meaningless.
- A score of **4** (perfectly contains all information) means that the code summarization is perfectly correct and perfectly contains all necessary information.

### Evaluation Steps:
1. Read the code carefully and understand the functionalities of the implementation.
2. Read the code summary and compare it to the code. Check if the code summary covers the functionalities of the code.
3. Assign a score for Content Adequacy on a scale of 0 to 4, where 0 is the lowest and 4 is the highest based on the Evaluation Criteria.

---

Code Snippet:

{{CODE}}

Summary for Evaluation:

{{GeneratedSummary}}

Evaluation Form: 
Content Adequacy (scores ONLY):

```

```
You will be given the code summary for a code snippet.
Your task is to rate the summary only on one metric.
Please make sure you read and understand these instructions carefully.
Please keep this document open while reviewing, and refer to it as needed.

### Evaluation Criteria:
Content Adequacy (0-4)** The Content Adequacy is measured by assessing the extent to which the summary lacks information needed to understand the code.

- A score of **0** (lacking all information) means that the code summarization is totally incorrect and meaningless.
- A score of **4** (perfectly contains all information) means that the code summarization is perfectly correct and perfectly contains all necessary information.

### Evaluation Steps:
1. Read the code carefully and understand the functionalities of the implementation.
2. Read the code summary and compare it to the code. Check if the code summary covers the functionalities of the code.
3. Assign a score for Content Adequacy on a scale of 0 to 4, where 0 is the lowest and 4 is the highest based on the Evaluation Criteria.

---

Code Snippet:

`{CODE}}`

Reference Summary:

{{REFERENCE}}

Summary for Evaluation::

{{GeneratedSummary}}

Evaluation Form:  
Content Adequacy (scores ONLY):

```
