# Wirusologia 🧬

Klasyfikacja wirusa: 

 - skorzystaj z serwera VipTree i serwisu BLASTn (NCBI, baza "RefSeq Reference genomes (refseq_reference_genomes)" + filtr "Viruses (taxid:10239)") 

- pobierz 100 pierwszych trafień BLAST’a i pogrupuj je w gatunki korzystając z narzędzia Vclust 

 

Adnotacja funkcjonalna: 

- Wykorzystaj potok analityczny PHold aby przewidzieć geny wirusa oraz ich funkcje.  

- Zweryfikuj jego przewidywania przewidując domeny w zidentyfikowanych białkach narzędziem InterProScan. 

- Poszukaj genów dla niekodujących RNA korzystając z serwisu CMscan (EBI) 

 
Wypełnij zadanie na kanale zajęć w aplikacji Teams


Niżej znajdziesz tabelę w której znajdują się linki do narzędzi wykorzystywanych na zajęciach
| Nr | Link  | Opis |
|:---:|:---:|:---:|
| 01. | [Phold na Google Colab](https://colab.research.google.com/github/gbouras13/phold/blob/main/run_phold.ipynb) | Phold to narzędzie do adnotacji genomów bakteriofagów wykorzystujące homologię sttrukturalną białek |
| 02. | [Inter Pro](https://www.ebi.ac.uk/interpro/search/sequence/) | Klasyfikacja rodzin białek |
| 03. | [VipTree](https://www.genome.jp/viptree) | VipTree to serwer do generowania drzewa filogentycznego wirusów na podstawie porówania ich przewidywanych proteomów |
| 04. | [Infernal Cmscan](https://www.ebi.ac.uk/jdispatcher/rna/infernal_cmscan) | Infernal to zestaw narzędzi do wykrywania sekwencji (np. genów) niekodujących RNA na podstawie meodeli kowariancji (czestow wykorzystywana jest największa baza rodzinb ncRNA nazwana RFAM |
| 05. | [Vclust](https://afproject.org/vclust/) | Vclust przyrównuje sekwencje (meta)genomowe wirusa, oblicza *Average Nucleotide Identity* (ANI) i grupuje genomy wirusów w gatunki i rodzaje. |
| 06. | [Ugene](https://ugene.net/download-all.html) | Przeglądarka genomowa umożliwiająca inspekcję i "ręczną" poprawę adnotacji |
| 07. | [Folder z danymi](https://github.com/AvirFrog/Wirusologia/tree/main/Dane) | Folder z danymi - w README.md wszystko jest rozpisane |
