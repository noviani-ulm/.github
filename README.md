# TRADITIONAL SNACKS CHECKER
## (Tourism, Creative, and Digital Economy)
### _Team: C22-PS128_


#### _This is a Capstone Project from Bangkit 2022._
- Catur Krida Cahya Laksana (C7269J2325) - Cloud Computing - Universitas Mulawarman
- Yuda Pratama (A2269J2326) - Mobile Development - Universitas Mulawarman
- Muhamad Fauzan (A2269J2323) - Mobile Development - Universitas Mulawarman
- Yogi Prasetyo (M2006F0583) - Machine Learning - Universitas Brawijaya
- Noviani (M2247K2176) - Machine Learning - Universitas Lambung Mangkurat
- Chrisanto Puae Burongan (M7247K2178) - Machine Learning - Universitas Lambung Mangkurat

# Background of this App
Project Plans:
> Seeing the great potential of diversity that exists in Indonesia, which is an attraction for tourists to visit. We are thinking how to make this potential as a means to improve the economy of MSMEs in the region and how we can accommodate it.
Based on this, we thought of something that many MSMEs sell and have an attraction for tourists. And that's where we found the idea to elevate traditional snacks. Because snacks are usually not too expensive, so tourists are interested in buying them.
In addition, the fact that there are so many traditional snacks in Indonesia, often the Indonesians themselves don't even know the names or other details of the traditional snacks they meet. That's why we plan to create an application that helps users identify traditional snacks that they encounter, as well as find the closest MSMEs that sell them.

Planned Execution:
> We will collect a dataset of various regional snacks, but considering there are so many regional snacks, we only take a few local snacks as initial data.
Dataset in Train on CNN Machine learning model. Then the data is entered and integrated into an application by the Mobile Development and Cloud Computing Team.

The Conclusion/Results:
> The application is in the form of a Mobile App, the application can scan traditional snacks and issue related information. Including being able to find the location of the nearest seller.

# How This App Build
### [Cloud Computing]
- Create a Custom API for preprocessing image that will send to model AI
- Deploy the model AI to GCP and make the endpoint
- Create the Realtime Database in Firebase for keep the food detail
- Input the food detail to database
- Testing the Custom API and make a documentation
- Testing the app

### [Android]
- Application has a real-time connection using firebase
- Displays culinary locations around the user's current location
- Take pictures with food objects to get that culinary information
- Integration with the provided API
- Testing the app
- Application theme can adjust by according with user preference
- User have full control of their account

### [Machine Learning]
- Collecting Image data from Google Image 
- Build CNN model for Image Classification
- Show training visualization 
- Serve Model for Online Prediction

# Dataset Link:  
https://bit.ly/Dataset-Snackiest-App 

# Deployed Link: 
https://bit.ly/Snackiest-App 
