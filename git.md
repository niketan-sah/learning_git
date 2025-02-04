<h1> Learning git and github </h1>
<br>
<h2> Basic setup for git </h2>
<i>
<ol>    
<li>git config --global user.name "niketan" </li>
<li>git config --global user.email "mail id"</li>
<li>git config --global core.editor "code --wait"</li>
<li>git conifg --global core.autocrlf</li>
<li>git config --global -e ( use it to read or update above values)</li>
</ol>
</i>


<h2>Git essential </h2>
<ol>
<li>git init (to initialise)</li>
<li>git add . (to add )</li>
<li>git commit -m "commit msg"</li>
</ol>

<h2>Branching </h2>
<ol>
<li>git branch branchname</li>
<li>merge branch 'branch name'</li>
<li>git branch (show no. of branches)</li>
<li>git branch -d branchname (delete branch)</li>
<li>git branch -C (will create branch and switch)</li>
</ol>

<h2>Stashing </h2>
<ol>
<li>git stash (will bookmark our changes not save or delete the changes just will bookmark)</li>
<li>git stash apply (it will bring the stashed item)</li>
<li>git stash clear (will clear the stashed item from memory)</li>
</ol>


<h2> Three stages of git file </h2>
<ol>
<li> U - untracked </li>
<li> A - added or staged</li>
<li> C - commited</li>
</ol>


<h2>Git Status</h2>
<ol>
<li>
git status -s  (It will tell the file status in short of only files)
(?? untracked status /
A  Added /
AM modified )</li>
<li>git status (it will tell commit status in detail)</li>
<li>git log (it will tell in very short how many and with what name )</li>
<li>git log --oneline </li>
<li>git log --graph</li>
</ol>


<h2>Deleting Branch </h2>
<ol>
<li>git reset --hard HEAD~2
<br>
(here (HEAD~2) means go back from current position to 2 step back.)</li>
<br>
<li>Other options :- reset, soft, mixed and revert.</li>
</ol>

<h2> Github </h2>
<b>steps :</b>
<br>
<ol>
<li> main banda folder and initial files banaayega</li>
<li> ab usse github par daal de</li>
<li> collaborators add kare</li>

<li> saare bande us repo se cloning karein</li>
<li> [very imp] apni branch create kare</li>
<li> apna code usi branch mein likhe</li>
<li> complete hone par commit dein and push kar dein</li>
<li> inform karein teamate ko about the commit</li>
<li> merger banda fetch karega and merge karega </li>
</ol>
<br>
<br>


<h2>Uploading to git </h2>
<ol>
<li>git branch -M main</li>
<li>git remote add origin URL</li>
<li>git push -u origin main</li>
<li>git push -u origin branchname</li>
<br>
<li>stay in main branch and run command</li>
<li>git merge branchname</li>
<li>git push origin main</li>
</ol>