_Polish description for potential GitHub users with a sample repository and the contents of the README.md file_ 

---
0. : 'Możesz dodać plik README do swojego repozytorium, aby powiedzieć innym ludziom, dla ktörych projekt jest przydatny, co mogą zrobić z tym projektem i jak mogą go używać.'  
---

### O plikach README

Możesz dodać plik README do repozytorium, aby przekazać ważne informacje o projekcie. README, wraz z repozytorium licencją , wytyczne wkładu i kod postępowania , i wytyczne wkładu , komunikuje oczekiwania na projekt i pomaga zarządzać wkładami.

Aby uzyskać więcej informacji na temat dostarczania wytycznych dotyczących projektu, zobacz "[Dodawanie kodu postępowego do projektu](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project)" i  "[Konfigurowanie projektu dla zdrowego wkładu](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions)". 

**Spis treści**

[Automatycznie-wygenerowany spis treści do plików README ](https://github.com/extrazi/przyklad#Automatycznie-wygenerowany-spis-tresci-do-plikow-README)  
[Łącza do sekcji w plikach README i stronach obiektów blob ](https://github.com/extrazi/przyklad#Linki_do_sekcji_w_plikach_README_i_stronach_BLOB )   
[Względne łącza ścieżki do obrazów w plikach README ](https://github.com/extrazi/przyklad#Względne_łącza_i_ścieżki_obrazów_w_plikach_README)   
[Dalsze zagadnienia](https://github.com/extrazi/przyklad#Dalsze-zagadnienia) 

Plik README, wraz z [licencją na repozytorium ]( https://docs.github.com/en/free-pro-team@latest/articles/licensing-a-repository )  , wytycznymi dotyczącymi wkładu i [kodeksem postępowania ]( https://docs.github.com/en/free-pro-team@latest/articles/adding-a-code-of-conduct-to-your-project ) , pomaga w komunikowaniu oczekiwań dotyczących wkładu do projektu i zarządzaniu nim. 

README jest często pierwszym elementem, który goście zobaczą podczas odwiedzania Twojego repozytorium. 

Pliki README zwykle zawierają informacje na temat: 

* Co robi projekt 
* Dlaczego projekt jest przydatny 
* Jak użytkownicy mogą rozpocząć pracę z projektem 
* Gdzie użytkownicy mogą uzyskać pomoc dotyczącą projektu 
* Kto zajmuje się projektem i wnosi wkład w projekt 

Jeśli umieścisz plik README w katalogu głównym repozytorium, `docs` lub ukryty katalog `.github`, GitHub rozpozna i automatycznie wyświetli plik README odwiedzającym repozytorium.

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/repo-with-readme.png)

Jeśli dodasz plik README do katalogu głównego repozytorium publicznego o takiej samej nazwie co nazwa użytkownika, ten plik README automatycznie pojawi się na stronie profilu. Możesz edytować swój profil README z GitHub Markdown, aby utworzyć spersonalizowaną sekcję w swoim profilu. Aby uzyskać więcej informacji, zobacz "[Zarządzanie swoim profilem README](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)".

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/username-repo-with-readme.png)

<a id="Automatycznie-wygenerowany spis tresci do plikow README"></a>
### [Automatyczne-wygenerowane spis treści do plików README ]( https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes#auto-generated-table-of-contents-for-readme-files )

W przypadku renderowanego widoku dowolnego pliku Markdown w repozytorium, w tym pliku README, GitHub automatycznie generuje spis treści na podstawie nagłówków sekcji. Możesz przeglądać spis treści dla pliku README, klikając ikonę :m  menu w lewym górnym rogu z renderowanej strony.

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/readme-automatic-toc.png)

Auto-generowany spis treści jest domyślnie włączony dla wszystkich plików Markdown w repozytorium, ale możesz wyłączyć tę funkcję do repozytorium.

* Na GitHub przejdź do strony głównej.
* W ramach nazwy repozytorium kliknij :s **Ustawienia**.

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/repo-actions-settings.png)

* W obszarze "Funkcje" odznaczają **Spis treści**.

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/readme-automatic-toc-setting.png)

### [Linki do sekcji w plikach README i stronach BLOB ]( https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#section-links-in-readme-files-and-blob-pages )  

Wiele projektów używa spisu treści na początku pliku README, aby skierować użytkowników do różnych sekcji pliku. Możesz utworzyć łącze bezpośrednio do sekcji w wyrenderowanym pliku, umieszczając wskaźnik myszy nad nagłówkiem sekcji, aby wyświetlić łącze:

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/readme-links.png)

### [Względne łącza i ścieżki obrazów w plikach README ]( https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#relative-links-and-image-paths-in-readme-files )  

Możesz zdefiniować linki względne i ścieżki obrazów w renderowanych plikach, aby ułatwić czytelnikom nawigację do innych plików w repozytorium. 
Względne łącze to łącze względne w stosunku do bieżącego pliku. Na przykład, jeśli masz plik README w katalogu głównym repozytorium i masz inny plik w docs/CONTRIBUTING.md, względne łącze do CONTRIBUTING.md w pliku README może wyglądać tak: 

 `[Wytyczne dotyczące wkładu dla tego projektu](docs/CONTRIBUTING.md)` 

GitHub automatycznie przekształci Twoje względne łącze lub ścieżkę obrazu w oparciu o gałąź, w której aktualnie się znajdujesz, tak aby łącze lub ścieżka zawsze działały. Możesz użyć wszystkich względnych operandów linków, takich jak ./ i ../ . 

Względne linki są łatwiejsze dla użytkowników, którzy klonują Twoje repozytorium. Łącza bezwzględne mogą nie działać w klonach repozytorium - zalecamy używanie odnośników względnych do odwoływania się do innych plików w repozytorium.


### Dalsze zagadnienia

* ["Dodawanie pliku do repozytorium"](https://docs.github.com/en/free-pro-team@latest/articles/adding-a-file-to-a-repository) 
* ["Dokonywanie czytelności plików README" ](https://github.com/18F/open-source-guide/blob/18f-pages/pages/making-readmes-readable.md) 18F
 
