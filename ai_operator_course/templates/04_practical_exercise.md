# Practical Exercise: [EXERCISE_TITLE]

**AI Agent Instructions:**
*   Replace `[EXERCISE_TITLE]` with a clear and descriptive title for the exercise.
*   Fill in all bracketed placeholders with specific details relevant to this exercise.
*   Ensure instructions are clear, step-by-step, and easy for learners to follow.
*   Define expected outcomes or deliverables clearly.

---

## Practical Exercise: [EXERCISE_TITLE]

**Associated Lesson(s):** `[Link to or name of the lesson(s) this exercise reinforces, e.g., Lesson: Understanding Key Monitoring Metrics]`

**Objective:**
`[Clearly state what the learner will achieve or demonstrate by completing this exercise. e.g., To set up a basic monitoring dashboard for a sample AI application using [Tool_Name].]`

**Scenario/Problem Statement:**
`[Provide a brief scenario or problem that the learner needs to address. e.g., "You are an AI Operator responsible for a newly deployed sentiment analysis API. Your task is to set up initial monitoring to track request volume, processing latency, and error rates."]`

**Prerequisites/Setup:**
*   `[Any software the learner needs to have installed, e.g., Docker Desktop, Python 3.8+, Access to [Specific_Cloud_Platform].]`
*   `[Any files or datasets that need to be downloaded or accessed. Provide links if possible. e.g., Download the sample application code from [Link_To_Repo/Files].]`
*   `[Any accounts or credentials required, e.g., A registered account on [Platform_XYZ].]`
*   `[Estimated time to complete this exercise: e.g., 1.5 hours]`

---

**Tasks / Steps:**

**Part 1: [Name of Part 1, e.g., Setting up the Environment]**

1.  **Step 1.1:** `[Detailed instruction for the first step. e.g., Clone the exercise repository: `git clone [repository_url]`]`
    *   Expected Output: `[Describe what the learner should see or achieve after this step, e.g., The repository is cloned to your local machine.]`
2.  **Step 1.2:** `[Detailed instruction. e.g., Navigate to the `exercise_1` directory: `cd exercise_1`]`
    *   Expected Output: `[e.g., Your command line prompt shows you are in the correct directory.]`
3.  **Step 1.3:** `[Detailed instruction. e.g., Install necessary Python packages: `pip install -r requirements.txt`]`
    *   `(Optional) Troubleshooting Tip:` `[e.g., If you encounter issues, ensure your Python version is 3.8 or higher.]`

**Part 2: [Name of Part 2, e.g., Configuring the Monitoring Tool]**

1.  **Step 2.1:** `[Detailed instruction. e.g., Start the [Tool_Name] container using Docker: `docker run -d -p 9090:9090 [tool_image_name]`]`
    *   Expected Output: `[e.g., The container starts successfully, and you can access the [Tool_Name] UI at http://localhost:9090.]`
    *   `[IMAGE: Screenshot of the expected UI of the tool after successful startup]`
2.  **Step 2.2:** `[Detailed instruction. e.g., Configure a new scrape job in the `prometheus.yml` file to target the sample application.]`
    ```yaml
    # Example configuration snippet
    # - job_name: 'sample_app'
    #   static_configs:
    #     - targets: ['localhost:8080']
    ```
    *   Expected Output: `[e.g., The configuration file is updated, and [Tool_Name] reloads the configuration.]`

**Part 3: [Name of Part 3, e.g., Observing and Analyzing Metrics]**

1.  **Step 3.1:** `[Detailed instruction. e.g., Run the sample application: `python app.py`]`
2.  **Step 3.2:** `[Detailed instruction. e.g., Send some sample requests to the application using `curl` or Postman.]`
    *   Example `curl` command: `curl http://localhost:8080/predict -X POST -H "Content-Type: application/json" -d '{"text": "This is a great product!"}'`
3.  **Step 3.3:** `[Detailed instruction. e.g., In the [Tool_Name] UI, query for the `http_requests_total` metric. Observe how it changes.]`
    *   `[DIAGRAM: Example of a graph in the monitoring tool showing the queried metric]`
    *   Expected Output: `[e.g., You can see a graph showing the total number of HTTP requests over time.]`

---

**Deliverables/Verification:**
*   `[What should the learner submit or check to verify completion? e.g., A screenshot of your dashboard showing the tracked metrics.]`
*   `[e.g., The configuration file used for the monitoring tool.]`
*   `[e.g., Answer the following question: What was the average latency observed for the API? ]`

---

**Challenge (Optional):**
`[An optional, more advanced task for learners who want to explore further. e.g., "Try setting up an alert that fires if the error rate exceeds 5% for 5 minutes."]`

---

Congratulations on completing the practical exercise!
