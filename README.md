# Bank-
# Option A: clone then copy files inside the cloned folder
cd ..
git clone https://github.com/YourUsername/ChurnPrediction_Project.git
cd ChurnPrediction_Project
# copy your prepared files into this folder, then:
git add .
git commit -m "Add project files for CLO1, CLO2, CLO3"
git push origin main

# Option B: if you are already in local folder and remote has a README, set upstream then pull
git remote add origin https://github.com/YourUsername/ChurnPrediction_Project.git
git pull origin main --allow-unrelated-histories
git add .
git commit -m "Merge local project files"
git push -u origin main
