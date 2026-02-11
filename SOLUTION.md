# AWS Account Setup Lab - Solution

**Student Name:** Cielo Escobar
**Date Completed:** 02/02/26

---

## Exercise 1: MFA Configuration

### Screenshot:
![MFA Enabled](screenshots/mfa-enabled.png)

### Notes:
- Authenticator app used: Google Authenticator
- MFA setup completed successfully: Yes
- Backup codes saved: Yes

---

## Exercise 2: Billing Alerts

### Screenshots:

**Billing Preferences:**
![Billing Preferences](screenshots/billing-preferences.png)

**Billing Alarm:**
![Billing Alarm](screenshots/billing-alarm.png)

**SNS Confirmation:**
![SNS Confirmed](screenshots/sns-confirmed.png)

### Configuration Details:
- Alert threshold: $10
- Email confirmed: No
- Additional thresholds created (bonus): No

---

## Exercise 3: Account Alias

### Screenshot:
![Account Alias](screenshots/account-alias.png)

### Account Details:
- **Account Alias:** cielo-cloud
- **Sign-In URL:** https://cielo-cloud.signin.aws.amazon.com/console
- **Tested successfully:** Yes

---

## Exercise 4: Free Tier Dashboard

### Screenshot:
![Free Tier Dashboard](screenshots/free-tier-dashboard.png)

### Current Free Tier Usage Summary:

| Service | Current Usage | Free Tier Limit | Status |
|---------|--------------|-----------------|--------|
| EC2 | [X hours / 750 hours] | 750 hours/month | [Green/Yellow/Red] |
| S3 | [X GB / 5 GB] | 5 GB | [Green/Yellow/Red] |
| [Other services...] | | | |

### Notes:
- Any services approaching limits? No
- Any unexpected usage? No

---

## Exercise 5: Reflection Questions

### 1. Why is MFA important even for a personal learning account?

**Your Answer:**
MFA is important because even if it’s just a learning account, someone could get in and use my resources, change things, or even make me pay for stuff. It helps keep my account safe and not rely only on a password.

---

### 2. What would happen if you left your root user unprotected?

**Your Answer:**
If I leave the root user unprotected, someone could get full access to my account. They could delete things, change settings, create resources that cost money, and it would be really hard to get the account back. That’s why it’s important to protect it.

---

### 3. How do billing alerts help prevent unexpected charges?

**Your Answer:**
Billing alerts let me know if I’m getting close to a spending limit I set. That way I can do something, like stop using a service, before I get charged too much. It’s helpful so I don’t get surprised by extra costs.


---

### 4. What threshold did you set for your billing alert and why?

**Your Answer:**
I set the threshold to $10 because that was what was recommended for beginners. It’s a good amount because it’s not too much, but it gives me time to react if something starts costing more than expected. 

---

### 5. What is your account alias and why did you choose it?

**Your Answer:**
- **Alias:** cielo-cloud
- **Reasoning:** I picked this alias because it’s easy to remember and looks professional. It has my name and shows it’s for cloud stuff, so I don’t get it confused with other accounts.

---

### 6. What services are you currently using according to the Free Tier dashboard?

**Your Answer:**
I’m currently using:
	- AWS Glue
	- Amazon Simple Notification Service (SNS)
	- AWS Key Management Service (KMS)

I’m not really surprised by the usage because I’m just learning and exploring these services to practice.
---

## Bonus Challenges Completed (Optional)

### Challenge 1: Multiple Billing Alert Thresholds

- [ ] $5 threshold
- [ ] $25 threshold
- [ ] $50 threshold

**Screenshots (if completed):**
[Add screenshots here]

---

### Challenge 2: CloudTrail Enabled

- [ ] CloudTrail enabled
- [ ] Logging to S3 configured

**Notes:**
[Add any notes about CloudTrail setup]

---

### Challenge 3: AWS Trusted Advisor Reviewed

- [ ] Accessed Trusted Advisor
- [ ] Reviewed recommendations

**Key recommendations found:**
[List any recommendations you found]

---

## Lessons Learned

**What was the most challenging part of this lab?**

The most challenging part was starting to understand AWS and how everything works. There are a lot of services and settings, so it was a bit confusing at first.

---

**What would you do differently next time?**

Next time, I would take it slower and practice more with each service before moving on. I think with more practice, it will be easier to understand.

---

**What security practices will you implement going forward?**

I will make sure to always use MFA, protect my root user, monitor billing alerts, and follow best practices for IAM and access. 

---

## Checklist Before Submission

- [x] All required screenshots captured and saved
- [x] Screenshots are clear and show relevant information
- [x] All reflection questions answered thoroughly
- [x] Account alias documented
- [x] Free Tier usage documented
- [x] Work committed to Git
- [x] Pull request created
- [x] PR URL submitted to Student Portal

---

**Lab Completed By:** Cielo Escobar
**Date:** 02/02/26
