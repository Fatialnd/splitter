# Friends Expense Splitter

## Overview
Friends Expense Splitter is a simple React application that helps users manage and split expenses with friends. It allows users to add friends, keep track of who owes whom, and split bills easily.

## Features
- Add and display a list of friends
- Select a friend to view balance details
- Split a bill between the user and a selected friend
- Keep track of outstanding balances

## Technologies Used
- React (useState hook for state management)
- JavaScript (ES6+ features)
- HTML & CSS

## Components

### 1. `App`
The main component that manages state and renders the different parts of the application.
- Stores friends list
- Toggles the add friend form
- Handles friend selection and bill splitting

### 2. `Button`
A reusable button component that simplifies button rendering across the application.

### 3. `FriendsList`
Displays the list of friends and allows the user to select a friend.

### 4. `Friend`
Represents an individual friend, displaying their name, profile picture, and balance status.

### 5. `FormAddFriend`
A form to add new friends by entering their name and profile picture URL.

### 6. `FormSplitBill`
A form to split a bill with the selected friend, allowing the user to specify the bill amount and who is paying.

## How to Use
1. Start the application.
2. Click "Add Friend" to add a new friend.
3. Select a friend from the list to view their balance.
4. Use the "Split Bill" form to divide expenses.

## Setup Instructions
1. Clone the repository.
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the application:
   ```sh
   npm start
   ```
![Screenshot 2025-02-04 at 22 52 42](https://github.com/user-attachments/assets/427a6bd0-c4a5-4f12-838e-59c0e5395b63)

![Screenshot 2025-02-04 at 22 52 54](https://github.com/user-attachments/assets/c7da9741-8b3e-4cb6-8a86-dc82b971e183)
