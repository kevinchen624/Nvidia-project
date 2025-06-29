# Nvidia-project
We are doing a project about sign-language project which we retrained the resnet 18 model and aims to recognize the letter_N, letter_V, letter_D, letter_I and Letter_A in american sign langauge. All of these combines to make a word NVIDIA. 
# Categories
1.letter_N
2.letter_V
3.letter_D
4.letter_I
5.letter_A
# Setup
echo "sudo docker run --runtime nvidia -it --rm --network host --volume ~/nvdli-data:/nvdli-nano/data --device /dev/video0 nvcr.io/nvidia/dli/dli-nano-ai:v2.0.2-r32.7.1" > docker_dli_run.sh
chmod +x docker_dli_run.sh
./docker_dli_run.sh
# Training
dataset 50 pictures of each letter, trained for 15 epoches
# Trained Model
https://drive.google.com/file/d/1zHQxq8wVILHUwY87mY4hjahm5yUZ1Suz/view?usp=sharing
