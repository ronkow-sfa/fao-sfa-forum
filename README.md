## FAO-SFA Forum data files for hands-on exercise

Data are provided in two formats (csv and xlsx).

`data.xlsx` and `data.csv` contain identical raw data of six records.   
They are transformed into `data_processed.xlsx` and `data_processed.csv` respectively.

Use `data_processed.xlsx` or `data_processed.csv` in Power BI.

***

`rasff_2023_2024_2025.xlsx` is the dataset of validated RASFF notifications from 1 Jan 2023 to 31 Dec 2025.   
It contains two worksheets, named `labelled` and `transformed`.   

You can load the `transformed` worksheet in Power BI to plot charts.

`rasff_2023_2024_2025.csv` contains only the `labelled` data.

***

`product_labels.txt` and `hazard_labels.txt` are the lists of labels used to label the records.

`prompt.txt` is the Generative AI prompt explained in the presentation slides. 

Look through the labels in `product_labels.txt` and edit it to suit your needs. If you just need to monitor a number of specific food products, you can use a much shorter list of labels. A shorter list will help the Gen AI app to process the data faster. Remember to include a catch-all label such as "others".

***
### LABELLING DATA IN A GENERATIVE AI APP

To label your data, upload `data.xlsx` (or `data.csv`), `product_labels.txt` and `hazard_labels.txt` to a Generative AI app and copy/paste the prompt.

For the 2023 to 2025 dataset, you need to upload the data in small batches. Try uploading 100 records at a time. If the app can output the results in a few minutes, then you can try uploading more records. 

Remember to upload only the necessary fields: reference, date, origin, subject, hazards

If it cannot handle 100 records, consider signing up for a payment plan. Please check the app's information on how much data it can handle before you sign up for the payment plan.

***
### POWER QUERY

If you like video courses, I think this free course is quite good:

[https://trumpexcel.com/power-query-course/?utm_source=copilot.com](https://trumpexcel.com/power-query-course/?utm_source=copilot.com)

I think Power BI is quite intuitive to learn and use. Use it often and you will soon be able to plot more charts and build a simple dashboard.

Learning to use software is like learning any practical skill. The more you practise, the easier it gets.

Have fun!
