# Black-Belt

## Requirements

-   Install [Python 3.6.X](https://www.python.org/downloads/).
-   Install the required packages:

```bash
pip install -r requirements.txt
```

-   Switch your [Keras backend](https://keras.io/backend/) to CNTK by editing `keras.json` in `%userprofile%/.keras/`:

```json
{
    "floatx": "float32",
    "epsilon": 1e-07,
    "backend": "cntk",
    "image_data_format": "channels_last"
}
```

## Usage

```bash
jupyter notebook
```

You could also run the notebook with a GPU provided by Google at [Colab](https://colab.research.google.com/github/woctezuma/blackbelt/blob/master/00-classifier-zoo.ipynb).

## References

-   [Keras: applications](https://keras.io/applications/)
-   [Keras: Usage examples for image classification models](https://keras.io/applications/#usage-examples-for-image-classification-models)
-   [CNTK 301: Image Recognition with Deep Transfer Learning](https://cntk.ai/pythondocs/CNTK_301_Image_Recognition_with_Deep_Transfer_Learning.html)
-   [CNTK: Build your own image classifier using Transfer Learning](https://docs.microsoft.com/en-us/cognitive-toolkit/Build-your-own-image-classifier-using-Transfer-Learning)
