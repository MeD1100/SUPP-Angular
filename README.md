# SUPP-AngularFront

This repository is dedicated to the frontend part of the SUPP - Social User Profiling Plateform.

This application is created to predict the content of an arabic social media post that a user provides via a URL input in frontend. A backend prebuilt NLP model called AraBERT is used to make this happen. ( check my other repository to access this code )

Steps of work:

A user inputs the URL.
URL is transfered to backend and an algorithm of scraping is initiated pulling out all the different data that the post presents; such as texts, images, videos, urls, comments, reacts, shares etc..
The scraped information are saved in a specific MongoDB connection and are fetched to the user in frontend.
the AraBERT then, being pretrained and pretested on a global database already, uses the scraped text to make its direct prediction.
The prediction is fetched to frontend.
PS: This project was pushed using github LFS ( Large File System ) to override the 100MB limitation on adding large files to Github. So you just uncompress the .rar file after installation and there you go, you have the full frontend project ready in use.

Created by Mohamed RHIMI - A Tunisian Computer Science Engineer: https://www.linkedin.com/in/mohamed-rhimi/

Thanks you for reading.
