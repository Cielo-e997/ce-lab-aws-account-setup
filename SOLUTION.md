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

| EC2 | [X hours / 750 hours] | 750 hours/month | [Green/Yellow/Red] |
| S3 | [X GB / 5 GB] | 5 GB | [Green/Yellow/Red] |
| [Other services...] | | | |

### Notes:
- Any services approaching limits?  No
- Any unexpected usage? No

---

## Exercise 5: Reflection Questions

### 1. Why is MFA important even for a personal learning account?

**Your Answer:**
It’s important because even for a learning account, MFA adds an extra layer of security. This way, if someone ever gets my password, they still won’t be able to log in without the second verification step. It helps keep my account and data safe while I’m practicing.
---

### 2. What would happen if you left your root user unprotected?

**Your Answer:**
If I left my root user unprotected, anyone could have full access to my account. They could change settings, delete resources, or even make charges without me knowing. It’s really risky, so protecting the root user is essential.
---

### 3. How do billing alerts help prevent unexpected charges?

**Your Answer:**
Billing alerts help because they notify me when my usage reaches a set limit. That way, I can check my services or stop something before I get charged unexpectedly. It’s a simple way to stay on top of costs.

---

### 4. What threshold did you set for your billing alert and why?

**Your Answer:**
I set it at $10 for 1 datapoint within 6 hours because it’s the recommended setting. This way, I get notified if my estimated charges go above $10 in a short period, which helps prevent unexpected costs.

---

### 5. What is your account alias and why did you choose it?

**Your Answer:**
- **Alias:** cielo-cloud
- **Reasoning:** My account alias is cielo-cloud. I chose it because it’s appropriate for the context and easy for me to remember.

---

### 6. What services are you currently using according to the Free Tier dashboard?

**Your Answer:**
AWS Key Management Service, AWS Glue, Amazon Simple Notification Service

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

The most challenging part for me is still learning to navigate the AWS Management Console and understanding everything it involves.

---

**What would you do differently next time?**

I would keep practicing in the meantime so that navigating the AWS Management Console becomes easier and more natural, allowing me to complete tasks more confidently next time.

---

**What security practices will you implement going forward?**

I will keep using Multi-Factor Authentication (MFA) on my account, protect my root user at all times, and monitor my billing alerts regularly.

---

## Checklist Before Submission

- [ ] All required screenshots captured and saved
- [ ] Screenshots are clear and show relevant information
- [ ] All reflection questions answered thoroughly
- [ ] Account alias documented
- [ ] Free Tier usage documented
- [ ] Work committed to Git
- [ ] Pull request created
- [ ] PR URL submitted to Student Portal

---

**Lab Completed By:** Cielo Escobar
**Date:** 02/02/26
