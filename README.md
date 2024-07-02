# Co-creative Sketch Tracing: AI Painter

This project generates coloured oil paintings from black and white sketches input by the user.

- ‘model.png’ is a diagram of our model.
- ‘model_discriminator.h5’ is an HDF5 file flowchart describing the
functioning of the discriminator network of the GAN and ‘model_generator.h5’ is an HDF5 file flowchart describing the functioning of the discriminator network of the GAN from test subject.
- ‘model_discriminator_buildings4.h5’ is an HDF5 file flowchart describing the functioning of the discriminator network of the GAN and ‘model_generator_buildings4.h5’ is an HDF5 file flowchart describing the functioning of the discriminator network of the GAN from our initial analysis.
- The oil painting generated from our human subjects’ sketches by our system is saved in Jupyter notebooks as ‘test_Code.ipynb’. This was done for the system evaluation part.
- The result from our initial analysis of the building dataset can be seen in the Jupyter notebook ‘buildingsDataset.ipynb’.

  
The Python notebook can be RUN on any modern computer system, within an appropriate Python 3.7 environment with the following packages pre-installed:

- TensorFlow
- pydot
- graphviz

The system may be implemented and checked simply by RUNNING the Python Jupyter notebook ‘code_main.ipynb’.
