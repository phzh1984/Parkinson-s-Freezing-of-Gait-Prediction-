# Parkinson-s-Freezing-of-Gait-Prediction

Overview

This project for the Parkinson's Freezing of Gait (FOG) Prediction. It aims to address the detection of freezing of gait episodes, a common and disabling symptom in people with Parkinson's disease, using 3D accelerometer data.

Dataset Description

The dataset comprises lower-back 3D accelerometer data collected under various circumstances, including lab visits, home settings, and continuous recordings. The objective is to detect the start and stop of each freezing episode and classify three types of FOG events: Start Hesitation, Turn, and Walking.

Data Series

The dataset is organized into three main data series:

tDCS FOG (tdcsfog): Data collected in a lab setting during FOG-provoking protocols.

DeFOG (defog): Data collected in the subject's home during FOG-provoking protocols.

Daily Living (daily): Continuous 24/7 recordings from subjects, some of whom exhibit FOG symptoms, while others do not. This dataset is unannotated.

File and Field Descriptions

train/: Contains training data series in subfolders tdcsfog/, defog/, and notype/.

test/: Contains test data series with limited fields.

unlabeled/: Contains unannotated data series from the daily dataset.

tdcsfog_metadata.csv, defog_metadata.csv, and daily_metadata.csv: Metadata files for series in each dataset.

subjects.csv: Metadata for each subject in the study.

events.csv: Metadata for FOG events.

tasks.csv: Task metadata for series in the defog dataset.
