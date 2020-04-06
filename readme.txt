docker build -f "C:\Users\brenda.blanco\source\repos\dockertraining_Omar_Vargas\dockertraining_Omar_Vargas\Dockerfile" --force-rm -t dockertrainingomarvargasbase "C:\Users\brenda.blanco\source\repos\dockertraining_Omar_Vargas"
Note: as a comment for previous command, it ran succesfuly for me without removing the double quotes from the docker file copy content

docker images -a (to copy the image id for the fir the run command)

docker run --name Site1 -p 8085:80 fc6a68443a46

docker run --name Site2 -p 8086:80 -e "AppSettings:StoreName"="Plano" fc6a68443a46 
	