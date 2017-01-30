# Who_you_should_not_follow_Datasets
One of the problems with using social media platforms for political participation is the existence of hijacked hashtags. 
A  hashtag  is  considered  as  hijacked  when  it  is  used  for  a purpose  different  from  the  original  one. 
This dataset contains a group of hashtags that were classified as supporting hashtags, a group of hashtags classified 
as opposing hashtags, the tweets ids that were used as input to train a model, and the resulting users classification 
after applying the method proposed in the academic article  "Who You Should Not Follow: Extracting Word Embeddings from Tweets 
to Identify Groups of Interest and Hijackers in Demonstrations". 

Who_you_should_not_follow_Datasets contain json and txt files obtained by querying Twitter. The data corresponds to 
information generated during strikes agaist the government of Ecuador (2015 and 2016). In detail, the files are:


1. Supporting_hashtags.json

["#30s", "#revocatoriarodas", "#quitovigila", "#defensoresrc", "#azuaysinnebot", "#enlace430", 
 "#laoposicionviolentayciega", "#mintiendocomopaez", ... ]


2. Opposing_hashtags.json

["#ecuadorsecanso", "#ecuadorprotesta", "#marchaguayaquil", "#robolucion", "#yucaparacorrea", 
 "#avanzamospatria", "#todosmarchamos", ... ]


3. Training_corpus.txt

comision regim econom analisis #salvaguardias @asambleaecuador @vethowenchica http://t.co/gpptz5a50t

#ecuadoryacambio @mashirafael hombr mujer paz defend revolucion #alpasadonuncamas http://t.co/nswc8wff7a

#creemosenti @mashirafael #pasadonuncamas hij present futur #siguecorreasigue http://t.co/tn3vut4lry

planton #yodefiendomirevolucion central #distrito2 contig @mashirafael #alpasadonuncamas http://t.co/ehmuwd0dkd

vam permit vuelv pas nefast pas nunc #ecuadoryacambio .....


4. Tweets_ids.json

(tweet_id, date_tweet_creation), 126667 observations

[(578763843981176832, 'Fri Mar 20 03:43:47 +0000 2015'),

 (610472260500066304, 'Mon Jun 15 15:41:43 +0000 2015'),
 
 (610615553011679233, 'Tue Jun 16 01:11:07 +0000 2015'),
 
 (578238671972909056, 'Wed Mar 18 16:56:57 +0000 2015'),
 
 (578681226552291332, 'Thu Mar 19 22:15:30 +0000 2015'),
 
 (607916595130679298, 'Mon Jun 08 14:26:25 +0000 2015'),
 
 (616437096509763584, 'Thu Jul 02 02:43:51 +0000 2015'),
 
 (616438930574049280, 'Thu Jul 02 02:51:08 +0000 2015'),
 
 (616443190183350272, 'Thu Jul 02 03:08:04 +0000 2015'),
 
 (616626331682500609, 'Thu Jul 02 15:15:48 +0000 2015'), ...]


5. Users_classification_results.json
.....


We also provide all the necessary steps to reproduce the experiments on users classification 
in the paper referenced below. For more details on how these files were generated, we refer to the following 
scientific publication. We would highly appreciate if scientific publications of works partly based on the 
Who_you_should_not_follow_Datasets quote the following publication:

L. Recalde, J. Mendieta, L. Boratto, L. Terán, C. Vaca, and G. Baquerizo.
Who You Should Not Follow: Extracting Word Embeddings from Tweets to Identify Groups 
of Interest and Hijackers in Demonstrations. (2017) 
