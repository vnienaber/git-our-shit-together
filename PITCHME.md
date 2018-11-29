# Git Workshop - Let's git our shit together!

--- 

### Installation und Accounterstellung
- siehe `README` des Repositories
- `www.github.com/friep/git-our-shit-together`


---

### Partner up!

- Mona Lovalace Octocat
![Mona](images/mona-lovelace.jpg)
- Grace Hopper Octocat
![Grace](images/gracehoppertocat.jpg)

---

### Warum Git?

- Masterarbeit.docx
- Masterarbeit_v1.docx
- Masterarbeit_FINAL.docx
- Masterarbeit_FINAL_TimsKommentare.docx
- Masterarbeit_FINAL_FINAL.docx

---

![Help](https://media.giphy.com/media/phJ6eMRFYI6CQ/giphy.gif)

---

### Version Control to the Rescue!
- Beispiel: diese Präsentation. 

---

### Fork und Clone


@box[bg-blue text-black rounded](Repository#"A Git repository is a virtual storage of your project. It allows you to save versions of your code, which you can access when needed." ([Source](https://www.atlassian.com/git/tutorials/setting-up-a-repository)))

@box[bg-blue text-black rounded](Fork#"A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project." ([Source](https://help.github.com/articles/fork-a-repo/))

---

### Hands On 1 - Fork und Clone
 
#### Mona

@ol

- [https://github.com/friep/git-our-shit-together/](https://github.com/friep/git-our-shit-together/): Fork (oben rechts)
- `https://github.com/{USERNAME}/git-our-shit-together` öffnet sich
- unter Settings->Collaborators Grace hinzufügen

@olend

---

### Hands On 1 - Fork und Clone

#### Mona & Grace

![Git clone](images/gitclone.png)

@ol

- Gitkraken Clone Repo -> Clone with URL
- Kopierten Link unter URL eintragen

@olend


---

### Oh!

![Git clone error](images/gitclone_auth_error.png)


---

### Oh! - Nicht-Gitkraken

```
Cloning into 'git-our-shit-together'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
```

---

### SSH 

@ul 

- Download: 
    - prinzipell jede*r @fa[lock-open] über `https` --> @fa[github]: @fa[check]
    - `ssh`: vorherige Einrichtung ntowendig --> @fa[github]: @fa[question]
- Upload: nur authentifizierte Personen @fa[lock]
- --> @fa[github]: @fa[question]

@ulend

---

### Authentification - Passwort

- bei jedem Push GitHub Passwort eingeben
- beachte: clone `https://...` 

![Git clone](images/gitclone_https.png)

--- 

### Authentification - SSH
- public key, private key cryptography (siehe z.B. [Youtube](https://www.youtube.com/watch?v=AQDCe585Lnc))
- nur einmal einrichten -> 
- clone `ssh://...`

---

### Hands On 1.1: Gitkraken mit Github verbinden

@ol

- Gitkraken Profil (rechts oben)
- Preferences->Authentification->GitHub
- connect to GitHub
- Generate SSH key and add to GitHub

@olend

---

### Commit

@box[bg-blue text-black rounded](Commit#"A commit is the Git equivalent of a "save".[...] Git committing is an operation that acts upon a collection of files and directories." ([Source](https://www.atlassian.com/git/tutorials/saving-changes))

--> Commit = Ein "Speicherpunkt" in Git. 

--- 

### Go back in time! 

![Time Machine](https://media.giphy.com/media/Vqvr9BGv1vhDi/giphy.gif)

---

### Hands On 2 - Go back in time 

@ol

- `reset master to this commit`
- spiele mit: `hard`, `mixed`, `soft`
- `fast forward master to origin/master` (oberster commit)

@olend


---

### Commit

- Commit hält **Veränderungen** gegenüber dem vorherigen Commit fest
    - Änderungen von Dateien
    - Neuerstellung von Dateien
    - Löschung von Dateien
    - Umbenennung von Dateien
- ein Commit kann mehrere Änderungen beinhalten

---

### Adding und Staging Area 


![Staging Area](images/staging.png)

(Source: [https://git-scm.com/about/staging-area](https://git-scm.com/about/staging-area))

---

### Hands On 3 - einen Commit machen 

Grace + Mona

@ol

-  Change stuff!
- **GIT ADD** von den "Unstaged Files" Dateien **GIT ADD**en, die man in Git "speichern" möchte. 
- (halbwegs) aussagekräftige Commit Message schreiben
- **GIT COMMIT** 

@olend

---

### Git quizzed!

![Lokal](images/git_workflow_lokal_without_solution.png)

---

### Git quizzed!


![Lokal](images/git_workflow_lokal_with_solution.png)

--- 

### Alles auf meinem Computer - aber was ist mit Tim?

- Die Cloud! z.B.

@fa[gitlab]
@fa[github]

---

### Git Lokal und Git Remote 

... what? 

**Lokal**: dein PC
**Remote**: in der Cloud (GitHub, GitLab, ...)

![Gitkraken Origin Master](images/gitkraken_origin_lokal.png)

![Gitkraken Lokal Remote](images/gikraken_remote_lokal.png)

---


### Sync: Git Pull und Git Push

- Git Pull: neue Commits von GitHub downloaden
- Git Push: lokal erstellte Commits nach GitHub hochladen

![Push Pull](images/push_pull.png)

---

![Push the button](https://media.giphy.com/media/139lMwJ9ow7bKE/giphy.gif)

--- 


### Hands On 4 - Pull und Push

@ol

- Grace: Push 
- Mona: Pull 
- Mona: Push 
- Grace: Pull

@olend

--- 

### Git quizzed!

![Push Pull](images/git_workflow_with_github_without_solution.png)

--- 


### Git quizzed!

![Push Pull](images/git_workflow_with_github_with_solution.png)

---

pictures of error slides


---



---



