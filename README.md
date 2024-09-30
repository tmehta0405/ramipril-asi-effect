# ramipril-asi-effect

This program is aimed at predicting how effective Ramipril, an ACE inhibitor for hypertension, is and its properties in general. It employs ‘virtual departments’ where simulated properties of Ramipril such as molecular weight or binding efficiency are illustrated. The primary objective is to estimate a given target value referred crystallographically as Standard Value, which is an indicator on the activity of ACE inhibition.

This data is known as preparation data. In this case, this data is sample data of Ramipril including its molecular weight and other chemical properties which are important since they define how effective Ramipril will be as an ACE inhibitor.

This property prediction of the target property uses the "Standard Value" (for example IC50) as the target, to be achieved. This value indicates the effectiveness of Ramipril, by which ACE activity is inhibited thus facilitating blood pressure reduction.

Data Completion: The software inserts some missing values so as to simulate a realistic situation afterwards then fills the collection for the purposes of analyzing the data set in particular.

Knowing and improving the model: It uses one of the Random Forest predictors to model dependencies of the reference drug properties efficacy to the drug under treatment properties. The particular model’s performance was improved with some optimisation and changing the parameters seeking for better prediction performance.

Evaluating the Model: It assesses the extent to which the predictions deviate from the truth. Therefore, if the predicted figures of Ramipril and actual figures fall within the same range, then it can be concluded that the model understands the effectiveness of Ramipril enough.
