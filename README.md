# Basic idea
You can associate load and reps with each workout you post, and the time of posting is recorded itself.

# Functionality
There are 4 available functions (each having a separate API route):
### 1. Post a workout (POST /workouts)-
Upload a new workout with a title, load and reps.
### 2. Update a workout (PATCH /workouts)-
Update an existing workout.
### 3. Delete a single workout (DELETE /workouts/:id)-
Delete the workout having the specified title.
### 4. Get a workout (GET /workouts/:id)-
Get a single workout with the specified title.
### 5. Get all (GET /workouts)-
Get all posted workouts.
