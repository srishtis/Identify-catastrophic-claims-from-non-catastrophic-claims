# Identify catastrophic claims from non-catastrophic claims

I n most insurance companies after a new claim is lodged, the claims officer has one responsibility (among other tasks) to identify if the claim is associated with a catastrophic(CAT) event or not. He then tags the claim with a relevant code that uniquely marks which catastrophe caused that loss(CAT code). This manual process contains a chance for leakage to occur. The objective of the project was to identify claims that are related to a catastrophic event and had been potentially missed by the claims officer.

The problem used insurance claims data inclusive of the claims descriptions from a leading Australian insurer. The claim descriptions were used to create word-based features. These word-based flags (binary flags 1 or 0) served as predictors for Naive-Bayes classification model.
