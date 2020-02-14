# CelebA

PyTorch Loader for the CelebA dataset with the identities of the people in the images as labels.

# Step 1

Run downlad.sh: bash download.sh celeba (this script is from https://github.com/yunjey/stargan.git)

# Step 2

now, place the identeties (identity_CelebA.txt) next to the images. The directories would look like: stargan/data/celeba: "identity_CelebA.txt  images  list_attr_celeba.txt". You can also find the identities here:  https://drive.google.com/drive/folders/0B7EVK8r0v71pWEZsZE9oNnFzTm8 .

# Step 3

now, run the test_celeba-with-id.ipynb notebook to see how you can also get the ids. In case of question, email me at fmireshg@eng.ucsd.edu. 
