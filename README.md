<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

<img src="images/ChatGPT Image Oct 11, 2025, 10_15_22 AM.png" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/>

<em></em>

<!-- BADGES -->
<!-- local repository, no metadata badges. -->

<em>Finding the restaurant suitable for you</em>

</div>
<br>


## Overview
This project aims to help tourists discover restaurants in a selected city based on a photo of a dish, even if they don’t know its name.

Using the FoodDataset, I trained a model capable of recognizing 31 food classes with an accuracy of around 80%. I then processed OpenStreetMap data to extract restaurants in the chosen city and clustered them into 9 macro cuisines.

Each cuisine is associated with the relevant food classes.
When a user uploads a photo of a dish, the model predicts its class and the app recommends restaurants that are likely to serve it, providing an intuitive way to explore local cuisine without language barriers.

## Project Structure

```sh
└── /
	├── LICENSE
	├── cache
    ├── README.md
    ├── best_model.pth
    ├── reggio_emilia_map.html
    ├── requirements.txt
    └── restaurant-identifier.ipynb
```

## Getting Started

### Installation

Build from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    git clone git@github.com:GiorgioChecola/AIschoolUNIMORE.git
    ```

2. **Navigate to the project directory:**

    ```sh
    cd AIschoolUNIMORE
    ```

3. **Install the dependencies:**

	```sh
	pip install -r requirements.txt
	```

### Usage

Open `restaurant-identifier.ipynb` and run each cell.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contribution

This work represents the project work of the AI school offered from University of Modena and Reggio Emilia.