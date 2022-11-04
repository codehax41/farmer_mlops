# farmer_mlops

Some mlops work CMD:
i) git clone
ii) python get_data.py
iii) python process_data.py
iv) python train.py
v) dvc init
vi) dvc run -n get_data -o data_raw.csv --no-exec python get_data.py #(create yaml)
vii)dvc repro
viii) git add, commit, push


Then github actions we will create work flow:
i) folder directort -> .github/workflows/train.yaml
ii) git add, commit, push