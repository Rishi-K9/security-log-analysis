# Security Log Field Analysis

## **Objective**
To understand basic security event analysis using synthetic authentication logs.

## **Log Fields**
- **Timestamp:** Records when an event occurred.
- **User:** Identifies the account involved.
- **Source IP:** Identifies the network address.
- **Event Type:** Describes the event, such as LOGIN_SUCCESS or LOGIN_FAILURE.

## **Observations**
- User bob had three consecutive failed login attempts.
- User alice successfully logged in and changed her password.
- User admin had a failed login followed by a successful login.
- Repeated failures may indicate suspicious activity.

## **Conclusion**
Security logs help monitor user activity and identify suspicious events.

## **Outcome**
Identified key security log fields and learned basic security event analysis.
