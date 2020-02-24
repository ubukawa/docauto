# docauto
docker practice with hfu/autonomy

# How to used
git clone git@github.com:ubukawa/docauto  
cd docauto  
docker build -t docauto .  
docker run -it --rm -v ${PWD}:/data docauto  

cd autonomy  
npm install  
npm update  
vi config/default.hjson  
rake  
node index.js
