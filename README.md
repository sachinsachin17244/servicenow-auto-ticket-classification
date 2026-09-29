# servicenow-auto-ticket-classification

# Auto Ticket Classification using ServiceNow Flow Designer

## Project Overview

This project automates IT helpdesk ticket classification using ServiceNow Flow Designer. The system analyzes incident information and automatically assigns the appropriate category based on keywords.

The goal is to reduce manual ticket classification, improve consistency, and speed up incident handling.

## Objective

Automatically classify incident tickets based on keywords found in the Short Description and Description fields.

### Main Objectives

- Automate incident classification.
- Reduce manual effort for IT support teams.
- Improve ticket categorization accuracy.
- Speed up incident processing.
- Provide consistent classification for similar issues.
- Automatically notify users after classification.

## Classification Logic

| Keywords | Ticket Category |
|---|---|
| Wi-Fi / Internet | Network Issue |
| Projector / Display | Hardware Issue |
| Password / Login | Account Issue |
| Slow Computer / System | Performance Issue |

## Flow Designer Process

1. Trigger when a new Incident is created.
2. Read the Short Description and Description.
3. Check for relevant keywords.
4. Identify the ticket category.
5. Update the Incident category.
6. Send an email notification.

## Workflow Automation

The Flow Designer workflow automatically processes newly created incidents.

**Incident Created → Read Details → Check Keywords → Identify Category → Update Incident → Send Email**

## Key Features

- Automatic ticket classification.
- Keyword-based classification.
- Automatic incident category update.
- Email notification after processing.
- Reduced manual intervention.
- Consistent ticket handling.
- Easy-to-maintain Flow Designer workflow.
- Real-time processing when an incident is created.

## Example

### Input

**Short Description:**

`Wi-Fi not working in classroom`

### Detected Keyword

`Wi-Fi / Internet`

### Automatically Assigned Category

`Network Issue`

### Result

The incident category is automatically updated to **Network Issue**, and an email notification is sent to the user.

## Technologies Used

- ServiceNow
- Flow Designer
- Incident Management
- Email Notifications
- ServiceNow Incident Table

## ServiceNow Components

The project uses the following ServiceNow components:

- Incident Table
- Record Created Trigger
- Flow Logic / Conditions
- Update Record Action
- Email Notification
- Flow Designer

## Benefits

- Saves IT support time.
- Minimizes repetitive manual tasks.
- Improves workflow efficiency.
- Provides standardized incident categorization.
- Helps support teams process tickets faster.
- Makes the classification process easier to monitor.

## Future Enhancements

The project can be extended with:

- Machine Learning-based ticket classification.
- Natural Language Processing (NLP).
- More incident categories.
- Priority prediction.
- Automatic assignment to support groups.
- Automatic incident prioritization.
- Dashboard for classification statistics.
- Integration with email and messaging systems.
- Classification based on both keywords and historical incidents.

## Testing

The workflow can be tested using different incident descriptions such as:

| Test Input | Expected Category |
|---|---|
| Wi-Fi is not working | Network Issue |
| Projector is not displaying | Hardware Issue |
| Cannot login to account | Account Issue |
| Computer is running slowly | Performance Issue |

## Project Output

The completed workflow automatically:

1. Detects a newly created incident.
2. Reads the incident details.
3. Searches for relevant keywords.
4. Determines the appropriate category.
5. Updates the incident record.
6. Sends an email notification.

## Screenshots

The project screenshots demonstrate:

1. Creating a new ServiceNow incident.
2. Configuring the Incident Created trigger.
3. Creating the Wi-Fi ticket condition.
4. Configuring the Update Incident Record action.
5. Complete Auto Ticket Classification workflow.
6. Automatically classified incident result.
7. Email notification / workflow execution result.

## Team Members

- Sachin A
- Srinivasan A
- VIGNESH WARAN B
- Naveen Kumar R
- Prajan Kumar S

## Conclusion

The Auto Ticket Classification project demonstrates how ServiceNow Flow Designer can automate a common IT service management task. By analyzing incident descriptions and applying predefined classification rules, the workflow automatically categorizes tickets and sends notifications.

This approach reduces manual work, improves consistency, and provides a foundation for future enhancements such as AI and machine-learning-based ticket classification.
