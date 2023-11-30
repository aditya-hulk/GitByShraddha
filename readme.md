![Alt text](image.png)

apne project ke code mein.. kab koyi file add hue, update hue delete hue.. sari info ye version control system track karte hai like Svn.

### Features
1) #### track the history
![Alt text](image-1.png)    
humne ek web page banaya.. uspe signup form fhir buttons banayai.. ab help page banane ke liye samay lag raha hia. hum chahte hai isse next phase mein design kare.. wapas signup button tak code chal jave.

ek to aap manually delete karo.. ya via git..

2) #### Collabaration  
konse changes konse devloper ne kiye..
 
--

# Github
![Alt text](image-2.png)

yaha hum apna code folder(repository) k form me store kar sakte hia.

### Create account in github
![Alt text](image-3.png)

![Alt text](image-4.png)


### Create a project in github
![Alt text](image-5.png)

![Alt text](image-6.png)

![Alt text](image-7.png)


### Commit code
![Alt text](image-8.png)

git me add aur commit dono karna padta hai..

Github mein direct commit ho jata hai.

![Alt text](image-9.png)

![Alt text](image-10.png)

# Setup git
![Alt text](image-11.png)

# Configuring git
![Alt text](image-12.png)

hum git ko bata rahe hai..ki konse account ke andar changes karne jaa rahe hai

![Alt text](image-13.png)

open git bash

![Alt text](image-14.png)

### U can open terminal from vs code also
![Alt text](image-15.png)


# Git Commands
![Alt text](image-16.png)

2 tarh se clone  
![Alt text](image-17.png)

# How to clone
![Alt text](image-18.png)

![Alt text](image-19.png)

git hub website se hum apne local machine me project lana chahte hai.

![Alt text](image-20.png)

yadi folder mein enter karna ho  
  cd folder name + tab
  ![Alt text](image-21.png)

### ls command
  ![Alt text](image-22.png)

### to view hidden files
ls -a 

ls -Hidden   
yadi .git dikh raha hai.. toh ye github ki file hai

### git status
![Alt text](image-23.png)

![Alt text](image-24.png)

## now add and commit
![Alt text](image-25.png)

![Alt text](image-26.png)

## WE have 4 status in git
![Alt text](image-27.png)

![Alt text](image-28.png)

![Alt text](image-30.png)

![Alt text](image-31.png)

## Add particular file
![Alt text](image-32.png)

## Add all
![Alt text](image-33.png)

## Commit
![Alt text](image-34.png)

![Alt text](image-35.png)


![Alt text](image-36.png)  
matlab  
aapne abhi local commit kiya hai.. abhi github par nhi dikhaya de raha hai..

![Alt text](image-37.png)

![Alt text](image-38.png)

![Alt text](image-39.png)

git push origin main -- not working

## Ab folder ko local se git hub par kaise pahuchaye
![Alt text](image-40.png)

Make a local directory
![Alt text](image-41.png)

![Alt text](image-78.png)

cd LocalRepo cmd make enter to LocalRepo

## Make it git folder
![Alt text](image-42.png)

Add commit
![Alt text](image-43.png)

Now we have to push this in new repository
## Now upload this in github

![Alt text](image-44.png)

Now create a new repo and push this in that repo

![Alt text](image-45.png)


![Alt text](image-46.png)

![Alt text](image-47.png)

## remote ly push kiya
![Alt text](image-48.png)

![Alt text](image-50.png)

![Alt text](image-79.png)

# Branch
![Alt text](image-49.png)  
alag log alag branch

![Alt text](image-51.png)  
aap main branch mein ho

## set branch new name
![Alt text](image-52.png)


# short form
![Alt text](image-53.png)

git push origin main

humne sare changes origin main mein push kar diye..
 humko ispar hi code changes karne hia

 git push -u origin main.. aage mein hu git push likhenge.. wo yahi push honge.

 ![Alt text](image-54.png)

 ![Alt text](image-55.png)
 This is workflow .. github mein repo bano  
 clone it  
   make changes  
   then add   
   then commit   
   then push

# Git Branches
### hum branch banate kyu hai?   
let say humari ek master branch hai. Aur hamare pass 3 developer hai.. aur har ek developer ko 1 feautre develope karna hai. So wo har feature ke liye nayi branch create kar lenga aur baad me master ke sath merge kar lenga.At a time sara kaam ho gya.

   ![Alt text](image-56.png)

![Alt text](image-58.png)

![Alt text](image-59.png)


![Alt text](image-60.png)

![Alt text](image-61.png)

![Alt text](image-62.png)
Now let's changes readme.md in feature1 branch.   
Ye jo bhi changes hai feature1 branch mein hue hai. 
![Alt text](image-63.png)

![Alt text](image-64.png)

# Now combine feaure1 and main branch

![Alt text](image-65.png)
 
 ![Alt text](image-66.png)

 ![Alt text](image-67.png)

 # 2nd way Pull Request
 humne feature1 branch mein kuch naya data add kiya hai, aur usse PR ke through merge karwa rahe hai

 ![Alt text](image-87.png)

 ![Alt text](image-88.png)
 ![Alt text](image-68.png)

 ![Alt text](image-80.png)

 ![Alt text](image-81.png)

 ![Alt text](image-69.png)

 ![Alt text](image-70.png)

 ![Alt text](image-71.png)

 ![Alt text](image-72.png)

 Abhi repository par main aur feature1 branch merge ho gya
 ![Alt text](image-84.png)
 ![Alt text](image-85.png)

 par jab mien apne local me check karta hu.. to local main branch mein to changes reflect nhi ho rahe hai

![Alt text](image-86.png)

 ![Alt text](image-73.png)

 Remote ke changes local mein lane k liye pull command

manlo remote branch mein kuch changes hue hai joh aapke local branch mein reflect nhi kar rahe hia.. so clone nhi karneka
pull karne ka.. sare changes reflect ho javenge  

git pull origin branch name

kiya hai implement succesfully

# Resolving Merge Conflicts
![Alt text](image-89.png)

dono branch mien aapne same line of code change kiye hai aur jab aap merge karne jate.. to git ko samjh nhi aata konse file ke changes merge karne hai

![Alt text](image-90.png)

![Alt text](image-91.png)

![Alt text](image-92.png)

![Alt text](image-93.png)

![Alt text](image-94.png)

![Alt text](image-95.png)

![Alt text](image-96.png)

![Alt text](image-97.png)

![Alt text](image-98.png)

# Undioing changes
![Alt text](image-99.png)

![Alt text](image-100.png)

![Alt text](image-101.png)

![Alt text](image-102.png)

# What happen in case of commit
![Alt text](image-103.png)
last commit ka nam head hai, Head~1 mane ek step piche
![Alt text](image-104.png)


![Alt text](image-105.png)

# git log
![Alt text](image-106.png)

write q to quit
# reset multiple commit
![Alt text](image-107.png)

har commit ka hash hota hai.. yadi piche jana hai toh uska hash head ke sath likho

![Alt text](image-108.png)

![Alt text](image-109.png)

# Fork
![Alt text](image-110.png)

![Alt text](image-111.png)

naya project serch kiya
![Alt text](image-112.png)

![Alt text](image-113.png)

![Alt text](image-114.png)
hamare isme aa gya

ab apne isme hum express project me khud se bhi change kar sakte




