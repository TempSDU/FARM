1. Please unzip img.zip to file img.
2. outfitlist_top.dat, traindata_top.dat, validdata_top.dat and testdata_top.dat are for top recommendation task. outfitlist_bottom.dat, traindata_bottom.dat, validdata_bottom.dat and testdata_bottom.dat are for bottom recommendation task.
3. The format of toplist is top_id, top_description_id, positive_bottom_id;
The format of bottomlist is bottom_id, bottom_description_id, positive_top_id;
The format of outfitlist.dat is top_id, bottom_id;
The format of outfitlist_top.dat and traindata_top.dat is bottom_id, top_description_id, positive_top_id;
The format of validdata_top.dat and testdata_top.dat is bottom_id, top_description_id, positive_top_id, candidate_top_id;
The format of outfitlist_bottom.dat and traindata_bottom.dat is top_id, bottom_description_id, positive_bottom_id;
The format of validdata_bottom.dat and testdata_bottom.dat is top_id, bottom_description_id, positive_bottom_id, candidate_bottom_id;
The format of descriptionlist.dat is description_id, description, item_id;
The format of vocab.dat is word_id, word, word_freq.
4. Note that change filenames in FARM.ipynb for different tasks. And unzip img.zip.
