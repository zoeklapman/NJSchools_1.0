# My First iOS App

## Introduction

This is my first iOS App from my CSSE337 Enterprise Mobile Apps class for college. Here was the objective of the assignment:

> The primary goal of this assignment is develop an app to list all K-12 schools in New Jersey and have the user enter a rating for schools. The app should be modeled similar to NJ Cities demo app presented in class - Use of 2 MVCs, (1) a list MVC using UITableViewController to list the schools and (2), a details MVC using UIViewController to show school details (name, type of school, address, city, phone number, current ratings) at the top in a UITableView, and an option to update the ratings using UISliderView at the bottom A Singleton Model should be used across two MVCs so the ratings changes in details MVC will be reflected in the list MVC.

## Description

The purpose of this app is to list all of the schools in New Jersey and assign ratings to chosen schools. A UITableViewController displays the data read from a JSON file. Clicking on a school in the list segues to a UIViewController that holds the details of the school and allows the user to update the school's rating.

![NJSchools1.0_List](/Images/NJSchools1.0_List.png)
![NJSchools1.0_Detail](/Images/NJSchools1.0_Detail.png)
