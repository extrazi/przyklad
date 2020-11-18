_Polish description for potential GitHub users with a sample repository and the contents of the README.md file_ 

---
1 O plikach README
---

Możesz dodać plik README do swojego repozytorium, aby powiedzieć innym ludziom, dlaczego Twój projekt jest przydatny, co mogą zrobić z Twoim projektem i jak mogą go używać.

**Spis treści**


[Łącza do sekcji w plikach README i stronach obiektów blob ](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#section-links-in-readme-files-and-blob-pages) 
[Względne łącza ścieżki do obrazów w plikach README ](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#relative-links-and-image-paths-in-readme-files) 
[Dalsze zagadnienia](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#further-reading) 

Plik README, wraz z [licencją na repozytorium ]( https://docs.github.com/en/free-pro-team@latest/articles/licensing-a-repository )  , wytycznymi dotyczącymi wkładu i [kodeksem postępowania ]( https://docs.github.com/en/free-pro-team@latest/articles/adding-a-code-of-conduct-to-your-project ) , pomaga w komunikowaniu oczekiwań dotyczących wkładu do projektu i zarządzaniu nim. 

README jest często pierwszym elementem, który goście zobaczą podczas odwiedzania Twojego repozytorium. 

Pliki README zwykle zawierają informacje na temat: 

* Co robi projekt 
* Dlaczego projekt jest przydatny 
* Jak użytkownicy mogą rozpocząć pracę z projektem 
* Gdzie użytkownicy mogą uzyskać pomoc dotyczącą projektu 
* Kto zajmuje się projektem i wnosi wkład w projekt 

Jeśli umieścisz plik README w katalogu głównym repozytorium, docs lub ukryty katalog .github, GitHub rozpozna i automatycznie wyświetli plik README odwiedzającym repozytorium.

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/repo-with-readme.png)

Jeśli dodasz plik README do katalogu głównego repozytorium publicznego o takiej samej nazwie jak Twoja nazwa użytkownika, ten plik README automatycznie pojawi się na stronie Twojego profilu. Możesz edytować swój profil README za pomocą GitHub Flavored Markdown, aby utworzyć spersonalizowaną sekcję w swoim profilu.

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/username-repo-with-readme.png)

## [Linki do sekcji w plikach README i stronach BLOB ]( https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#section-links-in-readme-files-and-blob-pages )  

Wiele projektów używa spisu treści na początku pliku README, aby skierować użytkowników do różnych sekcji pliku. Możesz utworzyć łącze bezpośrednio do sekcji w wyrenderowanym pliku, umieszczając wskaźnik myszy nad nagłówkiem sekcji, aby wyświetlić łącze:

 ![ilustracja - ](https://docs.github.com/assets/images/help/repository/readme-links.png)

## [Względne łącza i ścieżki obrazów w plikach README ]( https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes#relative-links-and-image-paths-in-readme-files )  

Możesz zdefiniować linki względne i ścieżki obrazów w renderowanych plikach, aby ułatwić czytelnikom nawigację do innych plików w repozytorium. 
Względne łącze to łącze względne w stosunku do bieżącego pliku. Na przykład, jeśli masz plik README w katalogu głównym repozytorium i masz inny plik w docs/CONTRIBUTING.md, względne łącze do CONTRIBUTING.md w pliku README może wyglądać tak: 

 `[Wytyczne dotyczące wkładu dla tego projektu](docs/CONTRIBUTING.md)` 

GitHub automatycznie przekształci Twoje względne łącze lub ścieżkę obrazu w oparciu o gałąź, w której aktualnie się znajdujesz, tak aby łącze lub ścieżka zawsze działały. Możesz użyć wszystkich względnych operandów linków, takich jak ./ i ../ . 

Względne linki są łatwiejsze dla użytkowników, którzy klonują Twoje repozytorium. Łącza bezwzględne mogą nie działać w klonach repozytorium - zalecamy używanie odnośników względnych do odwoływania się do innych plików w repozytorium.


**Dalsze zagadnienia**

* ["Dodawanie pliku do repozytorium"](https://docs.github.com/en/free-pro-team@latest/articles/adding-a-file-to-a-repository) 
* ["Dokonywanie czytelności plików README" ](https://github.com/18F/open-source-guide/blob/18f-pages/pages/making-readmes-readable.md) 18F
 
