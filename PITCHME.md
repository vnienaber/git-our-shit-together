# Git Workshop - Let's git our shit together!

--- 

### Installation und Accounterstellung
- siehe `README` des Repositories
- `www.github.com/friep/git-our-shit-together`


---

### Partner up!

- Mona Lovalace Octocat
![Mona](images/mona-lovalace.jpg)
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

### Hands On 1: Fork und Clone

@snap[north-west]
@box[bg-blue text-white rounded](Repository#Ordner, der mit Git versioniert wird. Ein Git(Hub) Projekt.)
@snapend

@box[bg-blue text-white rounded](Repo(sitory)#"A Git repository is a virtual storage of your project. It allows you to save versions of your code, which you can access when needed.")
@box[bg-blue text-white rounded](Fork#"A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.")

sources: [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/setting-up-a-repository), [GitHub Help](https://help.github.com/articles/fork-a-repo/)
---


### Commit
- Commit = Ein "Speicherpunkt" in Git. 

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

---

### Hands On 3 - einen Commit machen 

Grace + Mona

@ol

-  etwas verändern / löschen / hinzufügen / umbenennen (an **unterschiedlichen** Dateien!)
- von den "Unstaged Files" die Dateien **GIT ADD**en, die man in Git "speichern" möchte. Diese Dateien sind dann in der Staging Area. 
- eine (halbwegs) aussagekräftige Commit Message schreiben
- **GIT COMMIT** erstellt den Commit 

@olend

---

### Git quizzed!

![Lokal](images/git_workflow_lokal_without_solution.png)

---

### Git quizzed!


![Lokal](images/git_workflow_lokal_with_solution.png)

--- 

--- 

### Noch ein Bild
![Staging Area](images/staging.png)

(Source: https://git-scm.com/about/staging-area)
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


### Hands On 3 - Pull und Push

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



