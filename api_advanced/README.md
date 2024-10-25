eddit API Advanced Project

![API Badge](https://img.shields.io/badge/API-Advanced-blue)  
**Level:** Novice  
**By:** Tim Britton  
**Weight:** 1  

**Project Timeline:**  
- **Start Date:** Oct 20, 2024, 12:00 AM  
- **End Date:** Oct 26, 2024, 11:59 PM  

This project focuses on mastering API calls using the Reddit API. It's aimed at building comfort with APIs through practical experience, including recursive calls, pagination handling, JSON parsing, and dictionary sorting. Understanding APIs is a crucial skill, often tested in technical interviews and useful for personal development.

---

## 📚 Background Context

API usage is essential in various software applications and is a common topic in technical interviews. Mastering API usage, especially with a popular API like Reddit’s, can give you a significant advantage. This project is designed to help you become proficient with API documentation, endpoint handling, pagination, and JSON data management. 

---

## 🧑‍🏫 Learning Objectives

By the end of this project, you will be able to:
- Navigate API documentation to locate specific endpoints.
- Use APIs with pagination.
- Parse JSON data from API responses.
- Implement recursive API calls.
- Sort a dictionary by its values.

---

## 📋 Project Requirements

- **Editors Allowed**: `vi`, `vim`, `emacs`
- **Environment**: Ubuntu 14.04 LTS, Python 3 (version 3.4.3)
- **Formatting**: PEP 8
- **Code Execution**: All files must be executable.
- **Imports**: Libraries must be in alphabetical order.
- **Documentation**: All modules should be documented.
- **HTTP Requests**: Use the `requests` module for API interactions.

---

## 🚀 Tasks

### Task 0: How Many Subscribers?
**File**: `0-subs.py`  
Write a function that queries the Reddit API and returns the number of subscribers for a subreddit. If the subreddit is invalid, return 0.  
**Prototype**:
```python
def number_of_subscribers(subreddit)

