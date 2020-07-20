# Guided Project 03: Exploring Ebay Car Sales Data.

In this guided project, we'll work with a dataset of used cars from *eBay Kleinanzeigen*, a [classifieds](https://en.wikipedia.org/wiki/Classified_advertising) section of the German eBay website. The aim of this project is to clean the data and analyze the included used car listings.

The dataset was originally scraped and uploaded to [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database/data). DataQuest made the following modifications to the original dataset:

* DataQuest sampled 50,000 data points from the full dataset, to ensure your code runs quickly in our hosted environment
* DataQuest dirtied the dataset a bit to more closely resemble what you would expect from a scraped dataset (the version uploaded to Kaggle was cleaned to be easier to work with)

The data dictionary provided with data is as follows:

* `dateCrawled` - When this ad was first crawled. All field-values are taken from this date.
* `name` - Name of the car.
* `seller` - Whether the seller is private or a dealer.
* `offerType` - The type of listing
* `price` - The price on the ad to sell the car.
* `abtest` - Whether the listing is included in an A/B test.
* `vehicleType` - The vehicle Type.
* `yearOfRegistration` - The year in which the car was first registered.
* `gearbox` - The transmission type.
* `powerPS` - The power of the car in PS.
* `model` - The car model name.
* `kilometer` - How many kilometers the car has driven.
* `monthOfRegistration - The month in which the car was first registered.
* `fuelType` - What type of fuel the car uses.
* `brand`- The brand of the car.
* `notRepairedDamage` - If the car has a damage which is not yet repaired.
* `dateCreated` - The date on which the eBay listing was created.
* `nrOfPictures` - The number of pictures in the ad.
* `postalCode` - The postal code for the location of the vehicle.
* `lastSeenOnline` - When the crawler saw this ad last online.

The dataset is called `autos.csv` and is located in this Github folder, but can also be downloaded [here](https://drive.google.com/file/d/1H8-SUpdMpteA-Qvxn0F1Ad3Ek3z8lU1t/view?usp=sharing). 
