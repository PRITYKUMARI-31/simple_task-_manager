## How long did you spend on the coding test? 
ANS: I spent around three days on the coding test, focusing on implementing the core functionalities and ensuring that the code was well-structured and 
     met the project requirements.

## What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.
ANS: One of the most useful features added in the latest versions of JavaScript (ES2022) is the .at() method for arrays and strings. This method allows for 
     convenient access to elements at a given index, including support for negative indexing to access elements from the end of the array.
     example : 
     const tasks = ["Task 1", "Task 2", "Task 3"];
    // Access the last item using .at(-1)
    const lastTask = tasks.at(-1);
    console.log(lastTask); // Output: "Task 3"
    The .at() method enhances code readability and reduces the need for length-based indexing, making it especially useful for cases where the last element or
    any position-relative indexing is needed.

## How would you track down a performance issue in production? Have you ever had to do this?
ANS: Monitor Metrics: Use tools like New Relic or Datadog to track CPU, memory, and response times.
     Analyze Logs: Check logs with tools like ELK Stack or Splunk to identify anomalies or errors.
     Profiling and Tracing: Use tools like Chrome DevTools, Jaeger, or OpenTelemetry to identify slow functions or services.
     Database Optimization: Analyze slow queries with database profilers (e.g., MongoDB Profiler, MySQL EXPLAIN) and add indexes as needed.
     Load Testing: Simulate traffic using JMeter or Locust to confirm and isolate issues.
     Review Code and Dependencies: Check recent changes and libraries for inefficiencies and revert if needed.

## If you had more time, what additional features or improvements would you consider adding to the task management application?
ANS: If I had more time, I would consider adding the following features and improvements to the task management application:
     User Authentication: Enable user accounts to allow secure, personalized task management.
     Notifications and Reminders: Set up notifications for approaching deadlines and overdue tasks.












