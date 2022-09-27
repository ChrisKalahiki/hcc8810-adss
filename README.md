# RSSA for HCC8810 - Adaptive Decision Support Systems course

A merged copy of my [rssa-react](https://github.com/ShahanM/rssa-react) and [rssa-api](https://github.com/ShahanM/rssa-api) repositories but with only the relevant components for the HCC8810 - Adaptive Decision Support Systems class.

Only accepting pull requests from registered students in the class.

Updated 09-08-2022

## Getting Started
You need to run the frontend and backend separately. To run the front end, run the following commands in the root directory:
```
cd frontend
npm install
npm start
```

To run the backend, run the following commands in the root directory:
```
cd api/src/
python init_app.py
cd algs/
python train_implicitMF.py
python train_resampled_implicitMF.py
python ave_item_score.py
cd ..
python app.py
```

Updated 09-27-2022