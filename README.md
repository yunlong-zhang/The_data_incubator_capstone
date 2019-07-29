# The_data_incubator_capstone
This is my project for the semifinal challenge of The Data Incubator (TDI) application.

# Data Source.
Three datasets were used. temp_datalab_records_linkedin_company.csv (957 MB) was originally produced by LinkedIn and distributed by TDI email/blog. temp_datalab_records_social_facebook.csv (452 MB) was originally produced by Facebook and distributed by TDI email/blog. temp_datalab_records_job_listings.csv (only part 1, 25.16G) was originally produced by NYSE and distributed by TDI blog (https://blog.thedataincubator.com/tag/data-sources/).  All datasets are publicly accessible.

# Notebooks.
I choose those three datasets to build up an early-stage clean-up, processing and visualization notebooks. The notebooks here can be developed for larger dataset and more elaborate projects. For example, more NYSE data can correlate more companies to my visualization tool to render insightful thinking of the relationship between companies and their social media activities. The notebook can also be developed to a machine learning platform if enough data can be provided.

Two notebooks in the repositories: NYSE_execute.ipynb to process the large NYSE data chunk-by-chunk and save a small new csv file (AllCompanies.csv).  Company_social_media_activity.ipynb is the main notebook to finish the job.

# Proposal.
Based on my experience of job seeking, the social media activity of companies is important, not only for us to find the job openings, but also for the companies to show their robustness and vitality of a company.
The TDI blog provides a lot of useful datasets.  Among them, I selected three datasets, including a big one (~ 26G).  I would like to process and visualize the data to answer the following questions:  
(1) Is a company's Facebook activity is correlated to its LinkedIn activity? because as we all known, LinkedIn is more like a professional platform the companies to commute with consumers but Facebook is more casual.
(2) Is higher social media activity means higher recruiting willingness?  NYSE dataset provides the job counts of some companies. Note I didn't use the whole hundreds GB of data from NYSE. This notebook provides the platform to process the large data so other parts of NYSE data can be imported in the future.
(3) Is a successful company has more social media activity than less-successful company?
(4) Are LinkedIn followers, Facebook likes and Facebook talking-about correlated?
(5) Are those features related to a companies's revenuw? (This could be a machine learning project. Not in this notebook but highly possible in the future.)
(6) Big companies more active?  Simple answer is yes. but how to quantitatively measure it?
All the above question could be preliminarily answered by this project.  But a complete data science project needs more data and more elaborate analysis.  I would like to say the the notebooks here are only drafts of this project.
