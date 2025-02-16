# markdown in VScode 
## preview
```
press Ctrl + Shift + V 

```
## Snippets for Markdown
`Ctrl + Space`

## Go to header in workspace
Use `Ctrl+T` to search through head


## Math block:
$$
\displaystyle
\left( \sum_{k=1}^n a_k b_k \right)^2
\leq
\left( \sum_{k=1}^n a_k^2 \right)
\left( \sum_{k=1}^n b_k^2 \right)
$$

## inserting image 


![Link](https://img.icons8.com/?size=100&id=Li62CRyJSreB&format=png&color=FFFFFFFF)

and with drag and drop (Hold down Shift)
[PDF file](mit-book.pdf)

# Work whit GitHub 
## Configure Git 
```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```
## Clone the Repository
```bash
git clone https://github.com/your_username/your_repository.git
```
## Make Changes and Commit
```bash 
git add .
```
```bash
 git commit -m "Your commit message"
```
## Push Changes to GitHub
```bash
git push origin main
```
## Branching 
```bash 
git checkout -b new-feature
```
## Merging
```bash
git checkout main
git merge new-feature
```