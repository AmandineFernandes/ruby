## Une série d'exercices en Ruby
Série d'exercices qui vont se conclure par une très célèbre pyramide.

### Les exercices
Voici ce qui va se passer pour cet exercice : pour chaque sous-partie, nous allons créer un programme, afin de répondre à des questions ou de le faire marcher.

#### Bonjour monde
Créé un programme exo_01.rb qui affiche "Bonjour, monde !". 

#### Il ne dit pas bonjour
Reprendre le programme exo_02.rb, puis écrire un programme exo_03.rb qui est le même, mais avec # devant la ligne 2.

#### Ça marche pô 😢
Créé un programme exo_04.rb avec les lignes suivantes :
puts "Salut, ça farte ?

#### Opérations
Écrire un programme exo_05.rb avec les lignes suivantes :

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
Écrire un programme exo_06.rb avec les lignes suivantes :

number_of_hours_worked_per_day = 10
number_of_days_worked_per_week = 5
number_of_weeks_in_THP = 11
puts "Travail : #{number_of_hours_worked_per_day * number_of_days_worked_per_week * number_of_weeks_in_THP}"

Ajouter après la ligne suivante :
puts "Et en minutes ça fait : #{number_of_minutes_in_an_hour * number_of_hours_worked_per_day * number_of_days_worked_per_week * number_of_weeks_in_THP}"

#### Demander à l'utilisateur
Écrire un programme exo_07_a.rb avec les lignes suivantes :

puts "Bonjour, c'est quoi ton blase ?"
user_name = gets.chomp
puts user_name

Après, écrire un programme exo_07_b.rb avec les lignes suivantes :

puts "Bonjour, c'est quoi ton blase ?"
print "> "
user_name = gets.chomp
puts user_name

Enfin, écrire un programme exo_07_c.rb avec les lignes suivantes :

user_name = gets.chomp
puts user_name

#### Un programme qui dit bonjour
Écrire un programme exo_08.rb qui demande le prénom de l'utilisateur, et qui salut l'utilisateur avec "Bonjour, prénom !"

#### Un programme qui dit bonjour de manière complète
Écrire un programme exo_09.rb qui demande le prénom de l'utilisateur, qui lui demande après son nom de famille, et qui salue l'utilisateur avec "Bonjour, prénom nom !"

#### Un programme qui calcule des âges
Écrire un programme exo_10.rb qui demande son année de naissance à l'utilisateur, puis qui ressort l'âge que l'utilisateur a eu en 2017.

#### Un programme qui répète
Écrire un programme exo_11.rb qui demande un nombre à l'utilisateur, puis qui écrit autant de fois "Salut, ça farte ?"

#### Compter
Écrire un programme exo_12.rb qui demande un nombre à l'utilisateur, puis qui compte jusqu'à ce nombre.
