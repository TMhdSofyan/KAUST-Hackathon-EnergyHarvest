# KAUST-Hackathon-EnergyHarvest
There are two objective of this exercise:
- Develop a machine/deep learning model (sklearn or PyTroch) to predict cumulative oil production volume at 10 years.
- Develop machine/deep learning model(s) (sklearn or PyTroch) which is able to predict oil production rate at year 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 simultaneously (not the scenario of time window sliding that we know oil production rate at year 1, and then predict the same variable at year 2 or later years).

The basic deliverables are as followed:
- Using RMSE and R2 score metrics (without normalization) of testing data
- The parity (scattered) plot with true result and predicted value for testing data.

# Data
1000 simulation runs in total, and 120 time points per simulation run. There are to type of datasets that should be loaded which are paratamer and production dataset.

Data paramaterization as followed:
- Permeability x, y (Kxy, range: 50 to 500 md);
- Permeability anistropic ratio (Kxy/Kz, range: 1 to 100);
- Reservoir Thickness (H, range: 10 to 100 ft);
- Porosity (range 0.1 to 0.3);
- Bottom Hole Pressure (BHP, range: 200 to 1000 psia);
- Water Injection Rate (qinj, range: 1000 to 3000 STB/d).

# Preview
![example](/Screenshoot/Preview_Project.gif)
