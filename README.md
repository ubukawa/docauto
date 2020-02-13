# docauto
docker practice with hfu/autonomy

# How to used
git clone git@github.com:ubukawa/docauto  
cd dockout  
docker build -t docauto .  
docker run -it --rm -v ${PWD}:/data docauto  

cd autonomy  
rake  
