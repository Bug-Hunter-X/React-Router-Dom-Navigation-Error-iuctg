# React Router Dom Navigation Bug
This repository demonstrates a common error encountered when using React Router Dom for navigation.  The bug involves attempting to navigate between routes without properly using the `useNavigate` hook.  The solution shows the correct implementation.

## Bug Description
The initial code lacks the `useNavigate` hook to correctly trigger navigation when a button is clicked.  This results in the application not updating the URL or rendering the correct component.

## Solution
The solution utilizes the `useNavigate` hook from `react-router-dom` to programmatically change the route based on the button click. This enables the proper navigation to the desired '/about' route.