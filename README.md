# Security Log Analysis

## **Project Overview**
This project analyzes synthetic authentication logs to understand basic security event analysis.

## **Objectives**
- Identify timestamps, usernames, source IP addresses, and event types.
- Recognize repeated failed login attempts.
- Understand the importance of security logs.

## **Files**
- `sample_auth.log` — Synthetic authentication logs.
- `log_analysis.md` — Log field analysis and observations.

## **Methodology**
1. Created synthetic authentication logs.
2. Identified important log fields.
3. Reviewed authentication events.
4. Documented findings.

## **Key Findings**
- User `bob` had three consecutive failed login attempts.
- Successful logins, logout events, and password changes were identified.
- Repeated failures may require further investigation.

## **Deployment and Rollback**
This project analyzes sample logs and does not deploy a live system. Deployment configuration and rollback evidence will be documented separately.

## **Conclusion**
Security logs help monitor authentication activity and identify events that may require investigation.

## **Interview Questions**
**1. What is a security log?**

A security log records system or network events to help monitor activity and investigate threats.

**2. What is an event timestamp?**

An event timestamp records the date and time when an event occurred.

**3. Why are logs important?**

Logs help detect suspicious activity, investigate incidents, and monitor system security.

## **Disclaimer**
All sample logs are synthetic and intended for educational purposes.
