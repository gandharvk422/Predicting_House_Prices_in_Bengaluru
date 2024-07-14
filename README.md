# Predicting House Prices in Bengaluru

Welcome to the Predicting House Prices in Bengaluru project. This hackathon, provided by MachineHack.com, aimed to create a model to predict housing prices in Bengaluru using a dataset with various features describing each property.

## Hackathon Details

- **Hackathon Name:** [Predicting House Prices in Bengaluru](https://machinehack.com/hackathons/predicting_house_prices_in_bengaluru/overview)
- **Provided by:** [MachineHack](machinehack.com)
- **Profile Link:** [Gandharv Kulkarni](https://machinehack.com/user/65dd51b822401c0019068cb6)
- **Rank:** 302
- **Score:** 0.71379

## Problem Statement

What are the things that a potential home buyer considers before purchasing a house? The location, the size of the property, vicinity to offices, schools, parks, restaurants, hospitals or the stereotypical white picket fence? What about the most important factor -- the price?

Now with the lingering impact of demonetization, the enforcement of the Real Estate (Regulation and Development) Act (RERA), and the lack of trust in property developers in the city, housing units sold across India in 2017 dropped by 7 percent. In fact, the property prices in Bengaluru fell by almost 5 percent in the second half of 2017, said a study published by property consultancy Knight Frank. 

For example, for a potential homeowner, over 9,000 apartment projects and flats for sale are available in the range of ₹42-52 lakh, followed by over 7,100 apartments that are in the ₹52-62 lakh budget segment, says a report by property website Makaan. According to the study, there are over 5,000 projects in the ₹15-25 lakh budget segment followed by those in the ₹34-43 lakh budget category.

Buying a home, especially in a city like Bengaluru, is a tricky choice. While the major factors are usually the same for all metros, there are others to be considered for the Silicon Valley of India. With its help millennial crowd, vibrant culture, great climate and a slew of job opportunities, it is difficult to ascertain the price of a house in Bengaluru.

So what determines the property prices in Namma Bengaluru?

## Data Description

The train and test data consists of various features that describe properties in Bengaluru. This dataset is curated over months of primary and secondary research. Each row contains fixed size object of features.

### Features

1. **Area_type**: Describes the area
2. **Availability**: When it can be possessed or when it is ready (categorical and time-series)
3. **Location**: Where it is located in Bengaluru
4. **Price**: Value of the property in lakhs (INR)
5. **Size**: In BHK or Bedroom (1-10 or more)
6. **Society**: The society it belongs to
7. **Total_sqft**: Size of the property in sq.ft
8. **Bath**: Number of bathrooms
9. **Balcony**: Number of balconies

## Objective

With the given 9 features (categorical and continuous), build a model to predict the price of houses in Bengaluru.

## Files

- `Train.csv`: Training dataset
- `Test.csv`: Test dataset
- `Notebook.ipynb`: Jupyter Notebook containing the model building and evaluation process
- `requirements.txt`: List of dependencies for the project

## How to Use

1. **Clone the repository**:
    ```sh
    git clone https://github.com/gandharvk422/Predicting_House_Prices_in_Bengaluru
    ```

2. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    ```sh
    jupyter notebook Notebook.ipynb
    ```

## Results

- **Rank**: 302
- **Score**: 0.71379
- **Profile**: [Gandharv Kulkarni](https://machinehack.com/user/65dd51b822401c0019068cb6)

Feel free to explore and improve the model. Happy coding!
