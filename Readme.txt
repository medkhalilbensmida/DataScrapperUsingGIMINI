% you must have ANACONDA  in your system envirement path !!
% Install Dependencies
conda create -p venv python==3.10 -y
conda activate venv/      
pip install -r requirements.txt
% if you don't have streamlit installed 
conda install -c conda-forge streamlit
% To run the app :
streamlit run app.py