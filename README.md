# 2025 Love Data Week

## Repository contents
- `2025-02-love-data-week.ipynb` : Jupyter notebook created for 2025 Love Data Week workshop at the University of Waterloo Libraries.
### Sample data for analysis
While the notebook is more fun if you request your own Spotify thata, the following files contain mockup data that can be used for testing purposes.
- `Mock_Data_Set_Streaming_History_Audio_2020-2025_0.json` : AI-generated mock data set that can be used to test the Jupyter notebook.
- `Mock_Data_Set_Streaming_History_Audio_2020-2025_1.json` : AI-generated mock data set that can be used to test the Jupyter notebook.
- `Mock_Data_Set_Streaming_History_Audio_2020-2025_2.json` : AI-generated mock data set that can be used to test the Jupyter notebook.

## How to

### Option 1 : software install
To use the Jupyter notebook you will need to have Python and JupyterLab installed in your computer:
- [Download Python](https://www.python.org/)
- [Install JupyterLab](https://jupyter.org/install)

### Option 2 : use Project Jupyter's online version of JupyterLab

-[https://jupyter.org/try](https://jupyter.org/try)

### Option 3 : Google Colab
If you have a Google account:

#### Option 3.1 : Open the notebook directly in Google Colab
Use the following URL:

[https://colab.research.google.com/github/r-antoniomg/2025-love-data-week/blob/main/2025-02-love-data-week.ipynb](https://colab.research.google.com/github/r-antoniomg/2025-love-data-week/blob/main/2025-02-love-data-week.ipynb)

#### Option 3.2 : Download the `2025-02-love-data-week.ipynb` file and then open it in [Google Colab](https://colab.research.google.com/)

- Here is a short [video tutorial](https://youtu.be/R3sKKvMCwTo?si=5Ox2YZAKC90kNqDJ) that will guide you through the process

## Artificial Intelligence Disclosure [(AID) Statement](https://doi.org/10.48550/arXiv.2408.01904)

_Artificial Intelligence Tools_ : Gemini (no specified version) and Microsoft Copilot (University of Waterloo institutional instance). _Execution_ : Gemini and Microsoft Copilot were used to write and troubleshoot portions of the Python code in this Jupyter notebook. Microsoft Copilot was also used to create a random data set that can be used to test the notebook. The system was fed a single record using the data structure used by Spotify and the following prompt was used: 'Create 3 json files with 3500 records each, following the same pattern as the example file. The timestamp (ts) should be different for each record, with years ranging between 2020 and 2025-02. Throughout the dataset, include random duplicate records where all fields are identical except for the ts. Keep the ip_addr field exactly the same as the example in all records. The following fields should always have 'null' value: episode_name, episode_show_name, spotify_episode_uri, audiobook_title, audiobook_uri, audiobook_chapter_uri, audiobook_chapter_title, offline_timestamp. The following fields can be set to True or False at random: shuffle, skipped, offline, incognito_mode. The ms (miliseconds) field should contain a value between 60000 and 300000. Use real song names for the field master_metadata_track_name. Use real artist names for the field master_metadata_album_artist_name. Use real album names for the field master_metadata_album_album_name. Use made-up data for the 'platform' field. For each distinct master_metadata_track_name, generate a unique base62 string for the spotify_track_uri field. Make sure there are at least 200 distinct song names.'
