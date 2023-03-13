# Pix2Pix
An implementation of Image-to-Image translation with Conditional Adversarial Networks, implemented in Pytorch from scratch. 

The model was trained on the Maps dataset, and the results were obtained after training the model for 500 epochs. All the hyperparameters were set according to the original paper. 

|1st row: Input / 2nd row: Generated / 3rd row: Target|
|:...:|
|!.[.].(results/results_maps.png)|

### Training

To train this model from scratch, use

``` bash
    python -m train
```

You can change the hyperparameters by making change in the config.py before running train.py



