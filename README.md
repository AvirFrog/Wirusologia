# Wirusologia 🧬

Klasyfikacja wirusa: 

- skorzystaj z serwera VipTree aby umieścić swejego wirusa na drzewier filogenetycznym znanych sekencji bakteriofagowych
 
- znajdź i pobierz 100 podobnych sekwencji za pomocą usługi BLASTn (NCBI, baza "RefSeq Genome Database (refseq_genomes)" + filtr "Viruses (taxid:10239)") 

- pogrupuj je w gatunki korzystając z narzędzia Vclust (WRAZ ZE SWOIM WIRUSEM)

 

Adnotacja funkcjonalna: 

- Wykorzystaj potok analityczny PHold aby przewidzieć geny wirusa oraz ich funkcje.  

- Zweryfikuj jego przewidywania identyfikujac zakonserwowane domeny w przewidywanych białkach narzędziem InterProScan. 

- Poszukaj genów dla niekodujących RNA korzystając z serwisu CMscan (EBI) 

 
Wypełnij zadanie na kanale zajęć w aplikacji Teams


Niżej znajdziesz tabelę w której znajdują się linki do narzędzi wykorzystywanych na zajęciach
| Nr | Link  | Opis |
|:---:|:---:|:---:|
| 01. | [Phold na Google Colab](https://colab.research.google.com/github/gbouras13/phold/blob/main/run_phold.ipynb) | narzędzie do adnotacji genomów bakteriofagów wykorzystujące homologię sttrukturalną białek |
| 02. | [Inter Pro](https://www.ebi.ac.uk/interpro/search/sequence/) | identyfikacja zakonserowowabnych domen i rodzin białkowych |
| 03. | [VipTree](https://www.genome.jp/viptree) | serwer do generowania drzewa filogentycznego wirusów na podstawie porówania ich przewidywanych proteomów |
| 04. | [Infernal Cmscan](https://www.ebi.ac.uk/jdispatcher/rna/infernal_cmscan) | narzędzie do wykrywania sekwencji (np. genów) niekodujących RNA na podstawie meodeli kowariancji (usługa na stronie wykorzystuje największą baza rodzinb ncRNA - RFAM) |
| 05. | [Vclust](https://afproject.org/vclust/) | porównuje sekwencje genomów, oblicza *Average Nucleotide Identity* (ANI, miarę podobieństwa między genomami) i grupuje wirusy w gatunki i rodzaje. |
| 06. | [Ugene](https://ugene.net/download-all.html) | przeglądarka genomowa umożliwiająca inspekcję i "ręczną" poprawę adnotacji |
| 07. | [Folder z danymi](https://github.com/AvirFrog/Wirusologia/tree/main/Dane) | folder z danymi - w README.md wszystko jest rozpisane |
