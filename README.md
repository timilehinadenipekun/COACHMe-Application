# COACHMe-Application
COACHMe is a .NET MAUI app that simulates IoT-based athlete monitoring for football coaches. It tracks key metrics, predicts fatigue, readiness, injury risk, and performance, and includes drill assignments and dashboards. Promoting data-driven, ethical, and personalised training decisions.

Features:
Coach Dashboard: Displays team performance summaries, average fatigue, readiness, and top contributors.
Live Monitor: Shows real-time simulated athlete metrics such as heart rate, steps, distance, and calories burned.
Performance Charts: Visualises trends and progress using Microcharts.MAUI.
Rule-Based Predictions:
Fatigue Level (Low, Medium, High)
Performance Readiness (Fit to Play or Not)
Injury Risk (Low, Medium, High)
Predicted Match Contribution (Percentage Score)
Drill Assignment: Enables coaches to create, view, and store athlete drills with dates, intensity levels, and notes.
Local Data Storage: Uses JSON and CSV to ensure persistence and offline accessibility.

Technology Stack:
Framework - .NET MAUI (C# / XAML)
Architecture - MVVM
Charts - Microcharts.MAUI
Data Handling - JSON and CSV

How It Works:
The application loads athlete data from a local JSON file.
Simulated IoT metrics such as heart rate, sleep, and distance are loaded from CSV files.
A transparent, rule-based algorithm analyses these metrics to produce predictions for fatigue, readiness, injury risk, and performance contribution.
Drill assignments and dashboard summaries are stored locally and persist between sessions.

Methodology:
The project follows a data-driven approach to support intelligent coaching and athlete monitoring using simulated IoT input.
The rule-based prediction model was chosen for its transparency, reliability, and ethical interpretability, aligning with responsible AI use in sports technology.

Limitations:
Does not connect to live IoT or wearable devices.
No athlete-facing interface at this stage.
Cloud storage and multi-user functionality are not yet implemented.
Predictions are based on fixed conditions rather than adaptive or learning algorithms.

Future Improvements:
Development of an athlete interface for self-tracking and coach communication.
Machine learning integration for adaptive and predictive training recommendations.
Cloud synchronisation for cross-device data access and storage.

Author:
Timilehin Adenipekun
BSc Computing, University of Buckingham (2025)

This project is developed for academic and educational use.
All data is simulated and does not represent real individuals or actual athlete performance.
