# Formula1-data-analysis
Download data from https://ergast.com/mrd of Formula1 from year 1954 to 2021. Upload the data to Azure blob storage.
We are using 8 different dataset out of which four were Incrementally load on weekly basis.Also,we are transforming and generating into 4 different deltalake files.
Also analyzed the dominant drivers and domiant teams.
The Ingestion datasets schema are give below:-
![image](https://user-images.githubusercontent.com/43174715/172060368-e0ea7c13-2d03-4cae-ac0f-a9e1960b4a48.png)
![image](https://user-images.githubusercontent.com/43174715/172060452-536faafe-fe9d-4cae-9813-f3c61611c009.png)
![image](https://user-images.githubusercontent.com/43174715/172060473-cbd83f2d-7479-42d5-98a8-6d8ae9e08876.png)
![image](https://user-images.githubusercontent.com/43174715/172060488-0097ab10-45e6-4d64-b6ab-eeb15821a0cf.png)
![image](https://user-images.githubusercontent.com/43174715/172060521-fc6909ad-c929-4635-9a0a-cd886c2b6435.png)
![image](https://user-images.githubusercontent.com/43174715/172060543-356fe8b5-83ea-4321-863c-fdb4aec5a382.png)

The transformation dataset schema are given below:-

race_result dataset:-
![image](https://user-images.githubusercontent.com/43174715/172061190-87b06bf5-0868-44e8-bae5-2f942301b0a2.png)

drivers standing dataset:-
![image](https://user-images.githubusercontent.com/43174715/172061255-0ffd4af2-56c0-4bcd-9eb5-58b39f6a458f.png)

constructor standing dataset:-
![image](https://user-images.githubusercontent.com/43174715/172061361-9081c67c-196e-4156-9eff-f67f72c2e88a.png)

Calculated race_result dataset(normalized the points based on wins):-
![image](https://user-images.githubusercontent.com/43174715/172061468-9ba3964c-010b-4574-8953-e323b85d16b8.png)

dominant drivers of all time.
![image](https://user-images.githubusercontent.com/43174715/172063883-5ccf5644-67ad-4e87-aab6-78e00ca757eb.png)

domiant team of all time.
![image](https://user-images.githubusercontent.com/43174715/172063964-7e74381a-f07a-4637-958e-b2ed70fa7cc4.png)

