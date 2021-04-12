# Benchmarking Single Image Dehzing Methods Under Realistic Sunlight Haze
*Sun-Haze dataset* is a benchmark dataset for single image dehazing that include 112 hazy images with realistic sunlight haze. Since the ground truth of a hazy image could be a range of clean images, this dataset include 6 ground truth images (one original image plus 5 images retouched by 5 experts) per hazy image to provide the opportunity to test image dehazing methods in a more practical way. This dataset is built on top of MIT-Adobe FiveK dataset. Paper is [here](http://vlm1.uta.edu/~athitsos/publications/anvari_isvc2020.pdf).

# Sun-Haze Dataset 
Sun-Haze dataset is available [here](https://drive.google.com/file/d/1j4jV03ExUhIPYg-RYhr5mrUCyJwH0cQw/view?usp=sharingg).

# Analysis Results

## Quantitative Results

![alt text](https://github.com/zanvari/sun-haze/blob/main/figs/results.png?raw=true)

## Qualitative Results
![alt text](https://github.com/zanvari/sun-haze/blob/main/figs/results-images.png?raw=true)

# Publication
If you find this work useful for you, please cite:

    @inproceedings{anvari2020evaluating,
      title={Evaluating Single Image Dehazing Methods Under Realistic Sunlight Haze},
      author={Anvari, Zahra and Athitsos, Vassilis},
      booktitle={International Symposium on Visual Computing},
      pages={436--447},
      year={2020},
      organization={Springer}
    }

