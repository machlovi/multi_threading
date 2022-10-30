Docker file for this is machlovi/tf_threading:v2
machlovi/tf_threading:v1 need to download Mnist data from internet which I was facing error.

To run this do the following command as single

" bash threading.sh 1in1.yaml "

threading.sh has list for thread levels

Docker file for this is "machlovi/tf_threading:v4 "has both 5in1 and 1in1 file added with docker image which you can see in the docker file. So to run either file change the name when runing the bash command i.e

" bash threading.sh 1in1.yaml " to " bash threading.sh 5in1.yaml "


Incase it show file is no there
or you may can create a copy of yaml file and change the file name inside the cmd line within yaml file and run the above command