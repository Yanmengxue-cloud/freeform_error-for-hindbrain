# freeform_error-for-hindbrain
I can register the sample_brain dataset in brainreg using the parameters from Figure 1. But when I extracted a portion of the hindbrain from the sample_brain to form the sample_hindbrain dataset and attempted to register it using the same parameters, an error occurred during the freeform stage.   
The generated freemform.log and freemform.err files are empty. Brainreg is running in a newly created clean environment with python=3.12. In this environment, napari was installed using conda install -c conda-forge brainreg, and  conda install -c conda-forge napari. The versions are :napari (0.5.6) and brainreg (0.0.0).How can I modify the process to successfully register the sample_hindbrain dataset? My own data only contains partial hindbrain regions, and I cann't get full - brain data in my previous experioment.
- Figure 1: Parameters used for registering the sample_brain Image Layer.
- Figure 2: Successful registration of sample_brain.
- Figure 3: Registering the sample_hindbrain Image Layer using the same parameters.
- Figure 4: Error occurred in the freeform stage for sample_hindbrain.
- The data.zip contains two tiff files: sample_brain and sample_hindbrain.
