# LocalStorageDemo
Showing a friend how LocalStorage works :)

Simple example of how localStorage can be used to store inputs to a form and then populate them back if the form is reloaded.

Motivating use-case would be a simple survey that someone might fill out on separate occasions.

Obviously there's two main considerations with this:

1) Data will be lost if browser data is cleared

2) We shouldn't really be storing sensitive data in localStorage