# CipherByte
![Img](https://raw.githubusercontent.com/cyrixninja/CipherByte/main/screenshots/1.png)

For Screenshots [Visit](https://github.com/cyrixninja/CipherByte/blob/main/screenshots.md)
## About the Project
### Inspiration
 In a world where digital threats are escalating, we felt a deep need to empower users with knowledge and practical tools. This project is more than code; it's a passion to create a safer online environment.

The driving force is a belief in the power of knowledge. Beyond detecting phishing, we aim to educate users on cyber threats. This isn't just about defense; it's a call to action, inviting users to become advocates for cybersecurity. We envision a ripple effect of awareness and empowerment, shaping a resilient digital future.

### What it does
Cryptography Mini Games - This page helps you to learn about crptography and increase your knowledge about cybersecurity.

Phishing Quiz and Informations - This page helps us to spread awareness about the Phishing Attacks and help us stop it.

Phishing Email Detector - It’s an phishing email detector that would help you classify whether if an email you receive in your email is safe or not. We are using machine learning to classify whether if the email is safe or not. For the classification purpose we are use naive bayes algorithm and we are using dataset that we got from Kaggle to train the model. Just paste in the email you got in the input box and we’ll classify it for you.

Domain Analysis - This tool check the various data like SSL Certificates , Age of the domain (newer ones are more likely created for phishing or scams) and patterns that are found in other such domains .We are also using the whois api to get the data about the domain. When you enter the domain it goes through our various checks that will help us determine if the domain is safe. Just input the URL and we’ll provide you the report about it

### How we built it
We built it using Flask Backend and Python.We use Python Backend because we needed to use Machine Learning for Phishing Email Detection. We trained the data for it using publicly available dataset on kaggle. Other than that we used bootstrap for making our frontend.

### Challenges we ran into
The main challenge was to come up with an idea as cybersecurity is a very niche field and kinda hard to make a project in this domain.

### Accomplishments that we're proud of
That we were able to complete this project on time and make it as we wanted it to be.The Algorithm works efficiently and fast.

### What we learned
We learnt a lot about cybersecurity

### What's next for Cipher Byte
Integration with the database to keep log of reported phishing domains


## How to Run
Install Python before running as backend was made using python

### Install the requirements

```
pip install -r requirements.txt
```

### Run the Code

```
flask run
```