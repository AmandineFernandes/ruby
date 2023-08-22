## Une série d'exercices en Ruby
Série d'exercices qui vont se conclure par une très célèbre pyramide.

### Les exercices
Voici ce qui va se passer pour cet exercice : pour chaque sous-partie, nous allons te demander de créer un programme, et de soit répondre à des questions, soit de le faire marcher.

Nous te conseillons de tout mettre dans un joli repo Git, afin que tu t'entraines avec le programme de versionning.

#### Bonjour monde
Créé un programme exo_01.rb qui affiche "Bonjour, monde !". Voici les lignes qu'il doit avoir d'affichées lorsque tu l'exécutes :

$ ruby exo_01.rb
Bonjour, monde !
2.2. Bonjours, monde
Créé un programme exo_02.rb qui affiche les lignes suivantes :

$ ruby exo_02.rb
Bonjour, monde !
Et avec une voix sexy, ça donne : Bonjour, monde !
En faisant une recherche Google, peux-tu connaître la différence entre print et puts ?

#### Il ne dit pas bonjour
Reprends ton programme exo_02.rb, puis écris un programme exo_03.rb qui est le même, mais avec # devant la ligne 2. Peux-tu me dire ce qu'il se passe ?

#### Ça marche pô 😢
Créé un programme exo_04.rb avec les lignes suivantes :

puts "Salut, ça farte ?
Lance le programme. Que se passe-t-il ? Pourquoi ?

#### Opérations
Écris un programme exo_05.rb avec les lignes suivantes :

puts "On va compter le nombre d'heures de travail à THP"
puts "Travail : #{10 * 5 * 11}"
puts "En minutes ça fait : #{10 * 5 * 11 * 60}"

puts "Et en secondes ?"

puts 10 * 5 * 11 * 60 * 60

puts "Est-ce que c'est vrai que 3 + 2 < 5 - 7 ?"

puts 3 + 2 < 5 - 7

puts "Ça fait combien 3 + 2 ? #{3 + 2}"
puts "Ça fait combien 5 - 7 ? #{5 - 7}"

puts "Ok, c'est faux alors !"

puts "C'est drôle ça, faisons-en plus :"

puts "Est-ce que 5 est plus grand que -2 ? #{5 > -2}"
puts "Est-ce que 5 est supérieur ou égal à -2 ? #{5 >= -2}"
puts "Est-ce que 5 est inférieur ou égal à -2 ? #{5 <= -2}"
D'abord, que fait #{} ? Ensuite, mets un commentaire devant chacune des lignes et explique ce qu'elle fait.

#### Variables
Écris un programme exo_06.rb avec les lignes suivantes :

number_of_hours_worked_per_day = 10
number_of_days_worked_per_week = 5
number_of_weeks_in_THP = 11

puts "Travail : #{number_of_hours_worked_per_day * number_of_days_worked_per_week * number_of_weeks_in_THP}"

Ajoute après la ligne suivante :

puts "Et en minutes ça fait : #{number_of_minutes_in_an_hour * number_of_hours_worked_per_day * number_of_days_worked_per_week * number_of_weeks_in_THP}"
Lance-le programme. Que se passe-t-il ? Peux-tu l'expliquer ?

Astuce : même si ton programme affiche une interface en français (les puts), les variables doivent avoir des noms en anglais, afin d'éviter un franglais bizarre. Même si Marc utilise dans son cours des noms de variables en français, je pense que lui-même doit interdire ceci à Drivy et imposer des noms de variables anglais 😉

#### Demander à l'utilisateur
Écris un programme exo_07_a.rb avec les lignes suivantes :

puts "Bonjour, c'est quoi ton blase ?"
user_name = gets.chomp
puts user_name
Peux-tu me dire ce que fais gets.chomp ?

Après, écris un programme exo_07_b.rb avec les lignes suivantes :

puts "Bonjour, c'est quoi ton blase ?"
print "> "
user_name = gets.chomp
puts user_name
Enfin, écris un programme exo_07_c.rb avec les lignes suivantes :

user_name = gets.chomp
puts user_name
Quelles sont les différences entre les trois programmes ?

#### Un programme qui dit bonjour
Écris un programme exo_08.rb qui demande le prénom de l'utilisateur, et qui salue l'utilisateur avec "Bonjour, prénom !"

#### Un programme qui dit bonjour de manière complète
Écris un programme exo_09.rb qui demande le prénom de l'utilisateur, qui lui demande après son nom de famille, et qui salue l'utilisateur avec "Bonjour, prénom nom !"

#### Un programme qui calcule des âges
Écris un programme exo_10.rb qui demande son année de naissance à l'utilisateur, puis qui ressort l'âge que l'utilisateur a eu en 2017.

#### Un programme qui répète
Écris un programme exo_11.rb qui demande un nombre à l'utilisateur, puis qui écrit autant de fois "Salut, ça farte ?"

#### Compter
Écris un programme exo_12.rb qui demande un nombre à l'utilisateur, puis qui compte jusqu'à ce nombre.
