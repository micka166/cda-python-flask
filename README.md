```bash 
git pull origin main 

docker build -t my-fastapi-app .  

docker run -d --name my-container -p 6000:8000 my-fastapi-app