# bikesharing

Code ref: Pandas, Python 3.7.6, Jupyter notebook, Tableau

### Tasks
* Convert Citibike data to include `datetime` 
* Create worksheets and dashboards displaying Citibike data in interactive charts corrisponding with gender, trips, and bike usage
* Create a custom Tableau Story using the Citibike dashboards

### Overview of Project

The purpose of this analysis was to review Citibike data for a buinsess proposal mirroring the NYC bike sharing service in Des Moines IA. The August 2019 Citibike data was used for this analysis. Pulling data on gender, geographs, and user types to determin business feasability. 

### Link to Tableau Story:


## Dev 1: Convert datatypes:
Useing Python and Pandas "tripduration" was converted to `datetime` datatype by creating "new_tripduration" column.
Reference: Citibike_Challenge.ipynb

![Citibike_trip_code](https://user-images.githubusercontent.com/115188500/217838344-132ce67a-aef9-4aac-9bdf-5db4ae7d0666.png)

![Citibike_trip_check_type](https://user-images.githubusercontent.com/115188500/217838335-807e2018-b0a1-4090-ac53-4b5b4f068ebe.png)

## Dev 2:  Create Visualizations for the Trip Analysis
Tableau Public was used to create worksheets and dashboards vizualizing the data

### 1. All Users Checkout Times
[insert link to story page] Top usage of Citibike service is around 3000 minutes per user.
<img width="1225" alt="Citibike_userTrip" src="https://user-images.githubusercontent.com/115188500/217840734-bcbe1d7b-5225-470c-b98d-b9bbf4edaba8.png">

### 2. Gender Checkout Times
[insert link to story page] Checkout times for Males appears to be higher in frequency.
<img width="1226" alt="Citibike_genderTrip" src="https://user-images.githubusercontent.com/115188500/217841101-42e9ef21-299a-410e-b439-b639e2f19046.png">

### 3. Trips (Weekday per hour)
[insert link to story page] Peak riding hours are 6 - 10 am and 5 - 8 pm for weekdays. Weekend peaks are 5 am to 10 pm.
<img width="708" alt="Citibike_TripsWeekday" src="https://user-images.githubusercontent.com/115188500/217841876-76a9d408-fce2-4576-ba0f-6048c9902d8d.png">

### 4. Trips by Gender (Weekday per Hour)
[insert link to story page] Higher usage by Males during peak hours.
![Citibike_GenderUserType](https://user-images.githubusercontent.com/115188500/217843271-de4e044f-4cba-49e0-b05a-4e2023d15c71.png)


### 5. Trips by Gender  and User Type (Weekday per Hour)
[insert link to story page] Subscribers who are Male are the most frequent user types.
<img width="1225" alt="Citibike_Gender_trips" src="https://user-images.githubusercontent.com/115188500/217843690-4ea0d3ae-aee6-4b0d-902a-915ff01092aa.png">

## Summary:
* Male subscribers tend to be the highest users of the service at peak commute times during the weekdays.
* Female subscribers could be lured with additional marketing, potential for weekend leisure.
* The additional geographic maps below indicate strong trip starts and end locations closest to the inner city.

### Location Analysis

### 1. Ride Start Location
[insert story link] Start locations tend to gravitate to the inner city
![Citibike_Start_location](https://user-images.githubusercontent.com/115188500/217845901-eddbe631-d13e-4d5f-8a3c-6fedee8ecfeb.png)

### 2. Ride End Location
[insert story link] End locations tend to gravitate either on the western edge of the city or inner city.
![Citibike_End_Location](https://user-images.githubusercontent.com/115188500/217847287-a0f47d21-e942-4482-b5e3-470e34477520.png)



