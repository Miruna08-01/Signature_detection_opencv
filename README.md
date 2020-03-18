## Template pentru proiectele de Procesarea Imaginilor 2020.

Proiectul e facut sa "functioneze" cu git.

Pentru a lucra:

1) Cititi tutorialul de git si ssh: http://users.utcluj.ro/~visoft/tutoriale/
2) Faceti-va cont pe github daca nu aveti
3) Va setati ssh-ul sa puteti accesa github-ul
[4) Va puneti pe calculator git (nu cred ca trebuie GitExtensions sau kdiff3 deocamdata)] -> Experimental, poate nu trebuie git.
5) Va clonati proiectul specificat de profesor
6) In folderul proiectului va dezarhivati fisierele din aceasta arhiva: [TBD]
7) Deschideti Visual Studio, navigati la folderul proiectului, si deschideti. Upgradati daca vreti.
8) Compilati


Modificari in Visual studio:

Langa Solution Explorer exista un Team explorer. Mergeti pe iconita de Home si alegeti Settings.
Mergeti pana la Diff & Merge tool si alegeti Visual Studio.

Daca nu merge sa interactionati cu repository-ul remote:

Intrati in fisierul ``.gitconfig`` din folderul home (C:\users\xxx) si adaugati in sectiunea ``[core]``:

	sshCommand = ssh.exe

Daca tot nu merge, incercati sa dati comanda ``git fetch --all`` in folderul proiectului. Daca va da erori de cheie,

adaugati in variabilele de sistem (per user) ``GIT_SSH=C:\Windows\System32\OpenSSH\ssh.exe``

