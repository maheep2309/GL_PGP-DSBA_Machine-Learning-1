# GL_PGP-DSBA_Machine-Learning-1
This project predicts hotel booking cancellations using machine-learning models. It analyzes guest behavior, booking patterns, pricing, and market segments, then builds and tunes multiple classifiers to identify key cancellation drivers and help hotels reduce losses and optimize operations.

# Project Summary
This project tackles the rising issue of hotel booking cancellations by building a machine-learning solution that predicts whether a booking will be cancelled before the guest arrives. It begins with detailed exploratory analysis of 36,000+ bookings, examining trends in lead time, market segments, pricing, arrival patterns, guest history, and special requests. Key behaviors emerge—online bookings cancel more, long lead times increase uncertainty, repeated guests rarely cancel, and low-price or speculative bookings drive higher cancellation risk.

The dataset is cleaned, encoded, and split into train-test groups. Multiple models are developed: Logistic Regression, Naive Bayes, KNN, and Decision Trees. Each is evaluated using recall (critical for minimizing overbooking), precision, and F1-score. After addressing multicollinearity, tuning thresholds, running GridSearch, and applying pre- and post-pruning, the pre-pruned Decision Tree emerges as the best model.

It achieves high recall (~93%), strong F1 (~0.91), and consistent performance across train and test sets, making it both accurate and reliable. Feature importance reveals that lead time, online bookings, room price, special requests, arrival month, and group size heavily influence cancellations.

The project concludes with actionable strategies: dynamic cancellation policies based on lead time, targeted retention for online bookings, price-based interventions, seasonal policy adjustments, and using special requests as a commitment signal. These insights help hotels reduce revenue loss, optimize room allocation, and improve guest satisfaction.
