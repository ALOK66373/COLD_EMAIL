# 📧 COLD_EMAIL_GENERATOR
Cold_email_generator

**Imagine a scenario:**

This cold email is designed to effectively introduce Atliq’s software development services to Nike’s hiring team. It begins with a subject line that clearly conveys the value proposition—helping Nike accelerate software development by providing expert engineers. The opening line immediately establishes relevance by acknowledging Nike’s search for a Principal Software Engineer, showing that the sender is aware of their hiring efforts. This helps build an initial connection and increases the chances of engagement.

The email then highlights the common challenges of hiring, such as the time and resources spent on recruitment, onboarding, and training. It positions Atliq as a strategic partner by offering dedicated software engineers who can integrate seamlessly into Nike’s team. This approach not only saves time but also ensures that Nike gains access to highly skilled professionals without the delays and uncertainties of traditional hiring.

To encourage further discussion, the email includes a polite and open-ended call to action, inviting the recipient to schedule a quick call. The closing expresses genuine interest in hearing Nike’s thoughts and provides clear contact details for an easy follow-up. The overall structure ensures the message is concise, professional, and compelling—maximizing the likelihood of a positive response.

![img.png](imgs/img.png)

## Architecture Diagram
![img.png](imgs/architecture.png)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
