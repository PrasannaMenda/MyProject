SUMMARY
================================================================================

These files contain 1,000,209 anonymous ratings of approximately 3,900 movies 
made by 6,040 MovieLens users who joined MovieLens in 2000.
RATINGS FILE DESCRIPTION
================================================================================

All ratings are contained in the file "ratings.dat" and are in the
following format:

UserID::MovieID::Rating::Timestamp

- UserIDs range between 1 and 6040 
- MovieIDs range between 1 and 3952
- Ratings are made on a 5-star scale (whole-star ratings only)
- Timestamp is represented in seconds since the epoch as returned by time(2)
- Each user has at least 20 ratings

USERS FILE DESCRIPTION
================================================================================

User information is in the file "users.dat" and is in the following
format:

UserID::Gender::Age::Occupation::Zip-code




MOVIES FILE DESCRIPTION
================================================================================

Movie information is in the file "movies.dat" and is in the following
format:

MovieID::Title::Genres



How to run Python files
Before running the python, place the data files in desired location and copy the path into the function pd.read_csv.
For Eg:
If ratings.dat files is placed under D directoty and under certain folder as D://Project/Python_Files
Copy the path and place as below
pd.read_csv(r'D://Project/Python_Files/movies.dat',sep='::',header=None)
These files  help in providing the following outputs
find the total number of each genres
find the total number of each ratings with the graph
