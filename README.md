# Split Bill App

This repository contains a React application that helps users split bills with their friends. The app allows users to manage their friends, track balances, and handle the division of a bill between them and their selected friend.

## Features

- **Friend Management**: Users can add new friends to the app by providing a name and image URL.
- **Bill Splitting**: The app allows users to split a bill with a selected friend. Users can input the total bill value, how much they paid, and the app will calculate the balance.
- **Balance Tracking**: After splitting the bill, the app keeps track of how much each person owes or is owed. It displays a message indicating the current balance between the user and their friend.
- **Interactive UI**: The app provides an interactive interface to select friends, add new ones, and manage bill payments.

## Components

### 1. **App**

The main component that holds the state of the friends list, the selected friend, and whether to show the "Add Friend" form.

### 2. **FriendsList**

Displays the list of friends with their current balance and allows users to select a friend for bill splitting.

### 3. **Friend**

Represents an individual friend with a profile image, name, and the balance with the user. The user can select or deselect a friend here.

### 4. **FormAddFriend**

A form where users can add new friends by providing their name and image URL.

### 5. **FormSplitBill**

The form used for splitting a bill with the selected friend. Users can input the total bill value, their expense, and indicate who is paying the bill.

### 6. **Button**

A reusable button component used throughout the app.

## How It Works

1. **Adding a Friend**: Users can add friends by clicking the "Add friend" button and filling out the form with the friend's name and image URL.
2. **Selecting a Friend**: After adding a friend, users can select them to split a bill. The selected friend's balance will be updated based on the bill payment.
3. **Splitting a Bill**: When a friend is selected, users can input the total bill value, how much they have paid, and the app will automatically calculate the amount the friend needs to pay or is owed.
4. **Balance Update**: After the bill is split, the app updates the balances for both the user and the friend. It displays whether the user owes money, the friend owes money, or if they are even.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/split-bill-app.git
   ```
