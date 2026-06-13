# gemma4-color-picker

A demo that uses Gemma as a color picker with some interesting findings.

## Overview

This project demonstrates how to use Google's Gemma model for color picking tasks. It includes Jupyter notebooks exploring Gemma 4 12B's capabilities in understanding and working with color codes.

## Demo Visualization

### Color Prediction Results

> Analyse the color code (HEX code) of the seats in the image.

![Color Predictions](https://www.kaggleusercontent.com/kf/325700239/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..BmScPw1cQOcojjNODPe45Q.Uh-kY9nqOhE1Soq4z4wdO22GyIi_kos-3M3lBXG2kpzza4EJRzpMotjSyNs8HG1UpLCHvKV0YC2Ykxrp1af4IFZqJx3awOrnxPZU9-eCuyCkS6294XZvQJnd5P4WBUHvJAxN6iWEvdzzf4LV_F6v_zCnTom-viE5n7J4_QONNAw78X6ga40AlCotbbF3C7HE8p-8e5HC1DeAnozD8OR4OAIdXR3ijAP828U_-t51VQgwzikNKNmCcSBRqf6l-cLlugUhh0V4eSlQo7XbTuIBkG8yCpLRqYeEe-AFZKfzzdIl3MjcqIpvXW4XLCJWEIRGLkP2_0RLSJyZKs8LiyD6UE4NByPhYaKbSgPcQfOhbYHV5uLhT5VzsIWxvF_v5OALevnu2BBJn6_JoM1lILZykCkdimhodST9U3mWhNCscAxKkIwFIJt6_WIxJHCPCPet0WClw8XycOwYW6QHBtqpRJrzdusau0oW43RdMVETl08czmNZSzU1-mL2mvkkDMRuuKhESgFlb23JKD0Z1JtEjOVJ_NP_oAqVeCimsdWhHyr6ULflq82iCmhuXzSFd7Cz-6flsNjIutzVEptRI_I1WBwAC5J-oj82_QXk3eOpsye2AFI0B69KPJ4Kc3Ow8hGx.ns8Vktop5RIOogsmKMZoWg/__results___files/__results___8_0.png)

### Model Output Analysis
![Model Analysis](https://www.kaggleusercontent.com/kf/325700239/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..BmScPw1cQOcojjNODPe45Q.Uh-kY9nqOhE1Soq4z4wdO22GyIi_kos-3M3lBXG2kpzza4EJRzpMotjSyNs8HG1UpLCHvKV0YC2Ykxrp1af4IFZqJx3awOrnxPZU9-eCuyCkS6294XZvQJnd5P4WBUHvJAxN6iWEvdzzf4LV_F6v_zCnTom-viE5n7J4_QONNAw78X6ga40AlCotbbF3C7HE8p-8e5HC1DeAnozD8OR4OAIdXR3ijAP828U_-t51VQgwzikNKNmCcSBRqf6l-cLlugUhh0V4eSlQo7XbTuIBkG8yCpLRqYeEe-AFZKfzzdIl3MjcqIpvXW4XLCJWEIRGLkP2_0RLSJyZKs8LiyD6UE4NByPhYaKbSgPcQfOhbYHV5uLhT5VzsIWxvF_v5OALevnu2BBJn6_JoM1lILZykCkdimhodST9U3mWhNCscAxKkIwFIJt6_WIxJHCPCPet0WClw8XycOwYW6QHBtqpRJrzdusau0oW43RdMVETl08czmNZSzU1-mL2mvkkDMRuuKhESgFlb23JKD0Z1JtEjOVJ_NP_oAqVeCimsdWhHyr6ULflq82iCmhuXzSFd7Cz-6flsNjIutzVEptRI_I1WBwAC5J-oj82_QXk3eOpsye2AFI0B69KPJ4Kc3Ow8hGx.ns8Vktop5RIOogsmKMZoWg/__results___files/__results___14_1.png)

## Getting Started

### Run on Kaggle

The easiest way to run this code is on Kaggle:

👉 **[Open the demo on Kaggle](https://www.kaggle.com/code/alphadua/gemma-4-12b-color-code-demo)**

Kaggle provides a free GPU environment with all necessary dependencies pre-installed, making it perfect for exploring this Gemma-based color picker demo.

## Notebook: Gemma 4 12B Color Code Demo

### Algorithm

The demo uses Gemma 4 12B (a 12-billion parameter language model) to understand and predict color codes based on descriptive inputs. The approach leverages:

- **Gemma 4 12B Language Model**: Processes natural language descriptions and generates color code outputs
- **Color Code Generation**: Converts text descriptions (e.g., "a warm sunset orange") into standardized color codes (RGB, HEX, HSL)
- **Prompt Engineering**: Optimized prompts to guide the model toward accurate color predictions
- **Few-shot Learning**: Examples provided to the model to improve prediction accuracy

### Results & Findings

The notebook demonstrates:

- **High Accuracy**: Gemma 4 12B shows strong capability in mapping descriptive text to accurate color codes
- **Color Understanding**: The model can understand nuanced color descriptors and translate them to precise values
- **Interesting Observations**:
  - The model's color predictions are consistent and semantically meaningful
  - Complex color descriptions are handled well by the model
  - Potential use cases for automated color selection in design applications
  - Edge cases and limitations in color naming conventions

The demo includes visualizations of predicted colors, accuracy metrics, and comparative analysis of different color description styles.

## Contents

- **gemma-4-12b-color-code-demo.ipynb**: Main Jupyter notebook with complete implementation and results
  - [View on GitHub](https://github.com/auto-Dog/gemma4-color-picker/blob/d5f68038957655f9b8ef53b9c6c2d61be283eba2/gemma-4-12b-color-code-demo.ipynb)
  - [Run on Kaggle](https://www.kaggle.com/code/alphadua/gemma-4-12b-color-code-demo)

## Requirements

- Kaggle account (recommended for easy setup)
- Or local environment with:
  - Python >= 3.10
  - Jupyter Notebook
  - transformers >= 4.7.0
  - torch >= 2.4.0
  - Other dependencies as specified in notebooks

## License

Feel free to use and modify this demo for your own projects.
