# Data Science Docker Project Skeleton
Execute the following commands from command line in your workspace to make use of the skeleton for a new data science project. Replace placeholders.

```
git clone https://github.com/dvdmllr/skeleton.git
mv skeleton <NEW_PROJECT_NAME>
cd <NEW_PROJECT_NAME>
rm -rf .git
echo '' > README.md 
git init
docker build -t <CONTAINER_NAME> .
docker run -v $PWD:/home/jovyan/work -it --rm -p 8888:8888 <CONTAINER_NAME>
```
