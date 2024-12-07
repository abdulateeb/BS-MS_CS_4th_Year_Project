This dataset contains images of various recyclable materials, general waste, and household items for the purpose of waste classification and recycling research.

Dataset Structure:
The dataset is organized into a hierarchical folder structure as follows:

- images/
  - Plastic water bottles/
    - default/
      - image1.png
      - image2.png
      - ...
    - real_world/
      - image1.png
      - image2.png
      - ...
  - Plastic soda bottles/
    - default/
      - image1.png
      - image2.png
      - ...
    - real_world/
      - image1.png
      - image2.png
      - ...
  - Plastic detergent bottles/
    - default/
      - image1.png
      - image2.png
      - ...
    - real_world/
      - image1.png
      - image2.png
      - ...
  - ...

The "images" folder contains subfolders, each representing a specific waste category or item. The subfolder names serve as the labels for the respective categories.

Within each category subfolder, there are two folders:
1. "default": Contains standard or studio-like images of the waste item.
2. "real_world": Contains images of the waste item in real-world scenarios or environments.

All images in the dataset are in the PNG format.

Waste Categories:
The dataset covers the following waste categories and items:
- Plastic: water bottles, soda bottles, detergent bottles, shopping bags, trash bags, food containers, disposable cutlery, straws, cup lids.
- Paper and Cardboard: newspaper, office paper, magazines, cardboard boxes, cardboard packaging.
- Glass: beverage bottles, food jars, cosmetic containers.
- Metal: aluminum soda cans, aluminum food cans, steel food cans, aerosol cans.
- Organic Waste: food waste (fruit peels, vegetable scraps), eggshells, coffee grounds, tea bags.
- Textiles: clothing, shoes.

Dataset Usage:
-> It can be used for various waste classification and recycling research tasks.
-> Developing machine learning models for waste sorting and categorization.