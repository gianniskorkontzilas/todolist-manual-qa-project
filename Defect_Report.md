# Defect Report

## Bug-01
**Title:** Tasks Count -> Number of tasks left is always less than the real number by 1  
**Environment:** Chrome, Firefox, Edge, Safari, Android, iOS, iPad, Tablet  
**Steps to Reproduce:**
1. Add 3 tasks
2. Check the three tasks as done
3. Observe the number of tasks left

**Expected Result:**  
The number of tasks left should be zero.

**Actual Result:**  
The number of tasks left is (-1).

**Severity:** High  
**Priority:** High  
**Status:** Open

**Attachments:**  
- defect1.png



## Bug-02
**Title:** Task Formatting -> Inconsistent Space Display Between View and Edit Modes  
**Environment:** Chrome, Firefox, Edge, Safari, Android, iOS, iPad, Tablet  
**Steps to Reproduce:**
1. Create a new task with the title: “giannis.   kork.   kork” (including multiple spaces).
2. Save the task and observe how it is displayed in the list.
3. Edit the task and check how the title appears in the input field.

**Expected Result:**  
The task title should display the same spacing in both view and edit modes.

**Actual Result:**  
In view mode, only a single space appears between each word, but in edit mode, the original spacing is preserved.

**Severity:** Low  
**Priority:** Medium  
**Status:** Open

**Attachments:**  
- defect2.png




## Bug-03
**Title:** Incorrect Grammar in Placeholder Text  
**Environment:** Chrome, Firefox, Edge, Safari, Android, iOS, iPad, Tablet  
**Steps to Reproduce:**
1. Open the To-Do List application.
2. Locate the placeholder text inside the input field.

**Expected Result:**  
The placeholder text should be grammatically correct and display:  
“What needs to be done?”

**Actual Result:**  
The placeholder text displays:  
“What need’s to be done?”  
(incorrect apostrophe usage)

**Severity:** Low  
**Priority:** Low  
**Status:** Open

## Bug-03
**Title:** Incorrect Grammar in Placeholder Text  
**Environment:** Chrome, Firefox, Edge, Safari, Android, iOS, iPad, Tablet  
**Steps to Reproduce:**
1. Open the To-Do List application.
2. Locate the placeholder text inside the input field.

**Expected Result:**  
The placeholder text should be grammatically correct and display:  
“What needs to be done?”

**Actual Result:**  
The placeholder text displays:  
“What need’s to be done?”  
(incorrect apostrophe usage)

**Severity:** Low  
**Priority:** Low  
**Status:** Open

**Attachments:**  
- defect3.png



## Bug-04
**Title:** Filter -> Incorrect Scroll Position After Changing View Filter  
**Environment:** Chrome, Firefox, Edge, Safari, Android, iOS, iPad, Tablet  
**Steps to Reproduce:**
1. Add 100 tasks to the To-Do List.
2. Scroll to the bottom of the list.
3. Change the filter view from “All” to “Active” or “Completed”.
4. Observe the displayed content.

**Expected Result:**  
The system should reset the scroll position to the top when the filter is changed so users can immediately see the relevant tasks.

**Actual Result:**  
The system retains the scroll position at the bottom, which may make it appear as though no tasks are displayed, causing user confusion.

**Severity:** Medium  
**Priority:** Medium  
**Status:** Open


