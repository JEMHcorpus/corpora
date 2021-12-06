This repository contains a subset of the JEMH corpus to which vocalization diacritics, known as niqqud in Hebrew, have been manually added. 

Files included:
1. FullPreModernTestCorpus.txt: literary texts from the Ben-Yehuda Project, 11K
2. FullPreModernTrainingCorpus.txt: literary texts from the Ben-Yehuda Project, 120K
3. PremodernPostersTestCorpus.txt: ephemera - street ads, 15K

Since undiacritized Hebrew is written in plene form (with added matres-lectionis), a proper diacritization test entails input of plene text and output of normalized texts, with matres-lectionis identified and removed. Therefore, we have included all matres-lectionis in these files, but we have marked each case with a meteg character (unicode point 0x05BD). Note that only such letters that are not part of the normative spelling of the word are marked in this way. Thus, for example, the letter י in גִּיֽדּוּלוֹ is marked with a meteg, but not in לִי. 
