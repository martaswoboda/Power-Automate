# Power-Automate
# Email Auto-Delete Power Automate Flow

## Overview
This Power Automate flow automatically deletes emails from your inbox based on specific subject line criteria. It is designed for users who regularly receive emails they don’t need to keep (such as reports or notifications) but would like to delete automatically.

## How It Works
- The flow is triggered when a new email arrives in your inbox.
- The subject line of the email is evaluated against a set of conditions.
- If the subject matches any of the predefined conditions, the email is automatically deleted.
- If no match is found, the email remains in the inbox.

## Files in this Directory
- **Email_Auto_removing.pdf**: Contains screenshots of the flow, showing each step in detail.
- **README.md**: (This file) A brief overview of how the flow works and how you can implement it.

## Flow Description
1. **Trigger**: The flow starts when a new email arrives in your inbox using the “When a new email arrives (V3)” trigger.
2. **Condition**: It checks the subject line of the email against specific keywords using the “Condition” action. If the subject:
   - **Starts with** or **is equal to** the predefined values, the flow continues.
   - **Does not match** any condition, the flow stops.
3. **True Branch**: The matching email is deleted automatically using the "Delete email (V2)" action.
4. **False Branch**: No action is taken, and the email remains in your inbox.

## How to Use the Flow
1. Review the `Email_Auto_removing.pdf` file to understand how the flow is structured.
2. **Recreate the Flow** in your own Power Automate environment using the screenshots as a guide.
3. Modify the conditions in the **Condition** step to match the email subject lines you want to filter and delete.
4. Save the flow and let it run automatically when emails arrive in your inbox.

## Customizing the Flow
- **Modify Conditions**: You can easily add, remove, or edit the conditions to customize which emails are deleted.
- **Change Actions**: If you don't want to delete the emails, you can modify the action to move emails to a folder instead of deleting them.

## Screenshots
For a step-by-step guide, please refer to the `Email_Auto_removing.pdf` file included in this directory.
