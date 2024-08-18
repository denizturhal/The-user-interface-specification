# User Management Screen UI Guide

## Overview
This guide provides a clear outline of the features and functions on the User Management screen. This screen is where admins can create, update, and filter users in the system.

## UI Elements

### 1. **Top Bar**
   - **Add User Button:** 
     - **Text:** `+ New User`
     - **Action:** Opens the user form on the right to add a new user. The form includes fields for Username, Display Name, Phone, Email, Roles, and Account Status.
   - **Hide Disabled Checkbox:** 
     - **Text:** `Hide Disabled User`
     - **Action:** When checked, only shows users who are currently active.

### 2. **User Table**
   - **Columns:**
     1. **ID:**
        - **Purpose:** Displays a unique number for each user.
        - **Action:** Click to sort users by ID.
     2. **Username:**
        - **Purpose:** Shows each user's name.
        - **Action:** Click to sort users by name.
     3. **Email:**
        - **Purpose:** Shows each user's email.
        - **Action:** Click to sort users by email.
     4. **Status:**
        - **Purpose:** Shows if the user is active (`true`) or inactive (`false`).
        - **Action:** Click to sort users by status.

   - **Row Action:**
     - Click a row to select a user, which fills the form on the right for editing.

### 3. **User Form**
   - **Fields:**
     1. **Username:**
        - **Type:** Text Box
        - **Hint:** `Enter username`
        - **Note:** This is required. The system uses this as a unique identifier.
     2. **Display Name:**
        - **Type:** Text Box
        - **Hint:** `Enter display name`
        - **Note:** Optional. This is the name that appears on the UI.
     3. **Phone:**
        - **Type:** Text Box
        - **Hint:** `Enter phone number`
        - **Note:** Optional. You can add the user’s phone number.
     4. **Email:**
        - **Type:** Text Box
        - **Hint:** `Enter email address`
        - **Note:** This is required. The system uses this for notifications.
     5. **Roles:**
        - **Type:** Dropdown
        - **Choices:**
          - Guest
          - Admin
          - SuperAdmin
        - **Note:** This is required. You can select multiple roles to define the user’s access level.
     6. **Status:**
        - **Type:** Checkbox
        - **Text:** `Enabled`
        - **Action:** Check if the user account is active.

   - **Save Button:**
     - **Text:** `Save User`
     - **Action:** Saves the user details. If creating, it adds the user. If editing, it updates the user.

## User Journey

### Initial View
- The screen shows the user list and a blank form on the right.
- The `Hide Disabled User` checkbox is unchecked, showing all users.

### Steps to Use
1. **Adding a User:**
   - Click the `+ New User` button.
   - Fill out the form.
   - Click `Save User` to add the user to the list. The form clears afterward.

2. **Editing a User:**
   - Click on a user in the table.
   - The user’s details appear in the form.
   - Update as needed and click `Save User` to apply changes.

3. **Filtering Users:**
   - Check the `Hide Disabled User` box to see only active users.

## Accessibility Tips
- Ensure all form fields can be navigated by keyboard.
- Label all form elements clearly for screen readers.
- Enable sorting for keyboard and screen reader users.


