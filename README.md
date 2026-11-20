# credit-card-fraud-analysis-power-bi
Power BI dashboard analyzing 20K credit card transactions to uncover fraud patterns,including fraud rate by authentication method 
Objective
Help a fraud or risk team identify high-risk patterns across card types, authentication methods, channels, devices, locations and time of day, so prevention efforts can be focused where they matter most.

## Key Metrics

| Metric | Value
| Total Transactions | 20K |
| Total Fraud Cases | 339 |
| Fraud Rate | 1.70% |
| Total Fraud Value | $61.44K |
| Average Fraud Value | $181.25 |
| Legitimate Amount | $2.59M |

## Dashboard Sections

Fraud rate by card type:compares fraud rates across Amex, Discover, Visa, Mastercard and RuPay
Fraud % by authentication method: shows how each method (No Authentication, OTP, 3D Secure, PIN, Biometric) performs
Fraud % by channel and device type:** matrix of ATM, Contactless, In-App, Online and POS against Android, iPhone, Mac, ATM machine, POS terminal and smart watch
Domestic vs foreign transactions:split of fraud cases by transaction origin
AI scam fraud vs non-AI fraud:compares fraud rates between the two groups
Fraud cases by time of day: Early Morning, Morning, Afternoon and Evening

## Key Findings
Authentication matters most:Transactions with no authentication had a fraud rate of 4.44%, almost 6 times higher than biometric authentication (0.78%), the lowest of all methods.
 Card type differences are modest. Amex (2.01%) and Discover (1.96%) had the highest fraud rates, while RuPay (1.34%) had the lowest.
AI scam fraud is a major risk.The AI scam fraud rate was 9.07%, compared with 1.55% for non-AI fraud.
Fraud is concentrated in the early morning and morning. Each had 104 cases, together making up about 61% of all fraud, while the afternoon had the fewest (50).
Most fraud is domestic,266 cases (78.47%) were domestic and 73 cases (21.53%) were foreign.
Some channel and device combinations stand out,ATM transactions on Mac (3.00%) and smart watch (2.90%), and In-App transactions on Android phones (2.43%), had the highest rates.

## Suggested Actions

- Require stronger authentication (biometric, PIN or OTP) on transactions that currently have none
- Add extra monitoring for early morning and morning transactions
- Review controls on high-risk channel and device combinations
- Build detection rules and customer awareness around AI-driven scams

## Tools Used

- Power BI (data modeling, measures, visualization)

## Dataset

20,000 credit card transactions with a fraud flag.
Source: kaggle
Author:Perfect Kapesi 
