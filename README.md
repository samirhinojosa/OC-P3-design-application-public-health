# Design an application for public health [OC-P3]

## **Problem to solve**

The **"Public Health France"** agency has launched a call for projects to find innovative ideas for food-related applications. You want to participate and come up with an idea for an application.

## **Your mission**

After reading the call for projects, here are the different stages that you have identified:

1. Process the data set in order to locate relevant variables for future processing. Automate these treatments to avoid repeating these operations.
2. Throughout the analysis, produce visualizations to better understand the data. Perform a univariate analysis for each variable of interest, in order to synthesize its behavior.
3. Confirm or disprove the hypotheses using multivariate analysis. Perform the appropriate statistical tests to verify the significance of the results.
4. Develop an idea for an application. Identify arguments justifying the feasibility (or not) of the application from Open Food Facts data.
5. Write an exploration report and pitch your idea during the project defense.   

## **The data**

**The Open Food Fact** dataset is available on the official [website](https://static.openfoodfacts.org/data/en.openfoodfacts.org.products.csv). At the same time, you can check different types of files [here](https://world.openfoodfacts.org/data).

Variables are defined at this [address](https://world.openfoodfacts.org/data/data-fields.txt).

The fields are separated into four sections:

- General information on the product sheet: name, date of modification, etc.
- A set of tags: product category, location, origin, etc.
- The ingredients of the products and their possible additives.
- Nutritional information: amount in grams of a nutrient per 100 grams of the product.

For more details / information about, you can visit the following links
- [Open Food Facts](https://world.openfoodfacts.org/)
- [Nutri-Score](https://www.santepubliquefrance.fr/determinants-de-sante/nutrition-et-activite-physique/articles/nutri-score)

## **Repository file structure**

- notebook.ipynb: Notebook with the final work
- notebook_draft.ipynb: Pre-exploratory data analysis
- img: Images and graphs of the project
- supports: Folder with documents to support the work done
    - Project 3 presentation: Project presentation in French

### **Final note**

- The notebook is optimized to be used with **Jupyter lab**.
- The **datasets** should be located in folder called **datasets** in the root path