<p align="center">
    <img src="https://github.com/user-attachments/assets/46a5582d-64bb-4943-80eb-0b92d54740ec" alt="Karnataka Examination Authority" width="150"/>
</p>

# Seat Allocation by Karnataka Examination Authority

## Description
This project is a seat allocation system for students based on the Karnataka Examination Authority (KEA) rules. It assigns seats to candidates according to their rank, preferred college, category, and priority. The goal is to make the seat allocation process clear and efficient, helping students get into their chosen colleges based on merit.

## Overview
The seat allocation process follows these steps:

1. **Input Data:**
   - Candidate details including CET number, name, marks, rank, priority, and college code.
   - College seat availability data for various categories.

2. **Prioritization:**
   - Candidates are prioritized based on their ranks and the priority levels they have assigned to their preferred colleges.

3. **Seat Allocation Logic:**
   - For each candidate:
     - Check the availability of seats in the preferred college for the candidate's category.
     - Allocate a seat if available, considering:
       - The candidate's rank (higher ranks get preference).
       - The priority of the college selected by the candidate.
       - The category of the candidate (e.g., 1AG, 2AG, GM, GMH, SCG, STH).

