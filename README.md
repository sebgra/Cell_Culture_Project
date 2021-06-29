# Cell Culture project

Pretty simple image processing and classification academic project.

3 images are considered as 'angiokits' of a biological test to determine whether substance are promoting endothelial cell of human blood vessels. Cells are cultured on  human muscle cell substrate in Petri dish.

![3 Types of Cells](https://github.com/sebgra/Cell_Culture_Project/blob/main/Report_images/Start_images.png)


These substances may be used in future drugs to accelerate the growth of vessels in case of injury, or to slow them down to help fight certain malignant tumors. The images are provided courtesy of Sanofi and correspond to a real problem.


The idea was to create an image processing pipeline wich extract cells from background and try to seperate cells from each other by mathematical morphology technics. 

![Cells post-processed](https://github.com/sebgra/Cell_Culture_Project/blob/main/Report_images/Post_processed_cells.png)



Then two morphologic descriptors, perimeter and area of each cell is computed in order to discriminate growing types, by determining a boundary based on these two descriptors. 

![Cell separation](https://github.com/sebgra/Cell_Culture_Project/blob/main/Report_images/Graph_separation.png)

### Prerequisites

* Python
* Jupyter Notebook or Google Colab
* scikit-image

<br/>

## Install Python dependencies

```
conda install scikit-image

```

## Running the script

Open the notebook with Jupyter or Google Colab


## Built With

* [Python3](https://www.python.org/) - Language chosen
* [scikit-image](https://scikit-image.org/) - Used to read and process images.


## Authors

* **Sébastien Gradit** - *Initial work* - [sebgra's github](https://github.com/sebgra)

## License

This project is not under any license 

