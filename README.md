# conv2d-PS2

Used a modified U-Net model as per the paper on the same model published recently. 

Model was trained using Adam optimizer, with a cosine annealing scheduling (T_max = 10) and initial lr = 1e-4

Loss function used was MAE loss or L1 loss as used in the paper

Training was managed for 20 epochs at the time fo submission of the predictions form.

Loss convergence at the time of submission of the predicitions form was 0.0276 MAE

All code has been written from scratch including the model.

Saved weights for the best model at the time of submission of predictions form are uploaded on this repo for reference.
