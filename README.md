# odata-avps-drhfpnc

Open data des AVPs de la DRHFPNC

# 📑 Ressources

- Dataset Kaggle : [Avis de vacances de poste (AVPs) de la DRHFPNC](https://www.kaggle.com/datasets/adriensales/avis-de-vacances-de-poste-avps-de-la-drhfpnc)
- Notebook Kaggle : [⚙ Loader Avis de vacances de poste AVPs DRHFPNC](https://www.kaggle.com/code/adriensales/loader-avis-de-vacances-de-poste-avps-drhfpnc)
- Notebook Kaggle : [🧑‍🎓AVPs DRHFPNC for dummies](https://www.kaggle.com/code/adriensales/avps-drhfpnc-for-dummies)

# 🪄 Astuces

Générer le `pdf` structuré des AVPs:

```sh
pandoc all_avps_publies.md -o all_avps_publies.pdf --pdf-engine=xelatex --toc --toc-depth=1

```

```sh
pandoc all_avps_publies.md -o all_avps_publies.epub --toc --toc-depth=1

```
