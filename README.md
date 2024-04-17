# The Joy of Coding: ETL Project

## Project Context

In this project, we explore the concept of ETL (Extract, Transform, Load), which involves taking data from multiple unique sources, modifying it, and storing it in a centralized database. This practice is common when collecting data from various systems to utilize it in another system. The data may come in different formats such as CSV, JSON, XML, API requests with custom formats, or even from multiple databases with relatable data that needs to be merged into another database for insights.

## Presented Problem

Your local public broadcasting station has received an overwhelming number of requests for information on "The Joy of Painting." Viewers want a website that allows them to filter the 403 episodes based on the following criteria:

- **Month of original broadcast**: This will be useful for viewers who wish to watch paintings that were done during the same month of the year.

- **Subject Matter**: This will be useful for viewers who wish to watch specific items being painted.

- **Color Palette**: This will be useful for viewers who wish to watch specific colors being used in a painting.

The broadcasting station has already gathered data, but it is spread across multiple files and formats, making it unusable in its current form. They have also hired another team to build a front-end that allows viewers to filter episodes of "The Joy of Painting."

## Project Objective

Your task is to assist the broadcasting station in designing and building a database that will house the collected data in a usable format. Additionally, you will need to build an API to access the data from the database.

## Project Steps

1. **Data Extraction**: Gather the data provided by the broadcasting station from various sources and formats.

2. **Data Transformation**: Clean, preprocess, and transform the collected data into a consistent format suitable for storage in a database.

3. **Database Design**: Design a database schema that efficiently stores the transformed data and supports the desired filtering functionality.

4. **Data Loading**: Load the transformed data into the designed database.

5. **API Development**: Build an API that allows the front-end team to access and retrieve data from the database based on the specified filtering criteria.

6. **Testing and Validation**: Thoroughly test the ETL process, database, and API to ensure data integrity and proper functionality.

7. **Documentation**: Provide clear documentation on the database schema, API endpoints, and usage instructions for the front-end team.

## Expected Outcomes

- A well-designed database that efficiently stores the collected data related to "The Joy of Painting" episodes.
- An API that allows the front-end team to retrieve episode data based on month of original broadcast, subject matter, and color palette.
- Comprehensive documentation that facilitates seamless integration between the database, API, and front-end application.

By completing this project, I enabled the local public broadcasting station to provide their viewers with a user-friendly website to explore and filter episodes of "The Joy of Painting" based on their preferences.