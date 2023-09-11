# &Delta;Cp Prediction

Heat capacity (Cp) is a thermodynamic property which measures the amount of heat energy required to raise the temperature of a substance by a certain amount. In the context of proteins, heat capacity plays a significant role in understanding their stability and behavior. Heat capacity is related to the protein's ability to resist denaturation, which is the disruption of its native structure. Heat capacity determines, the amount of heat a protein can absorb with increase in temperature before its denaturation. The heat capacity of a protein often increases as it undergoes denaturation because energy is required to disrupt the various non-covalent interactions (e.g., hydrogen bonds, van der Waals forces) that stabilize the native structure. This change in heat capacity (&Delta;Cp) determines the protein stability, higher the value of &Delta;Cp, more stable the protein will be.
We prepared a machine learning model to predict &Delta;Cp of a protein from its sequence. The model is trained of sufficient dataset and is capable to yeild prediction with high accuracy.

## Dataset

The data on change in heat capacity on unfolding of protein was obtained from {ProTherm](https://web.iitm.ac.in/bioinfo2/prothermdb/) database. The obtained dataset was cleaned and curated to get more significant data. The frequency distribution of dataset is represented in fig. 1

![image](https://github.com/Growdeatechnology/Cp_prediction/assets/72397529/0c1f8054-45a6-4950-b103-f4dc2269bde6)

fig 1.Frequancy Distribution Initital Dataset

![image](https://github.com/Growdeatechnology/Cp_prediction/assets/72397529/b886f664-ec13-4120-8594-e0313119d099)

fig 2.plotting against Sequence length

![image](https://github.com/Growdeatechnology/Cp_prediction/assets/72397529/099191e0-a176-44a7-8e3b-b2e47fd3c602)

fig 3. prediction plot

![image](https://github.com/Growdeatechnology/Cp_prediction/assets/72397529/08d6f44c-3ff8-40f4-a336-bd091d8206fb)

fig 4. Prediction plot after removing outliers
