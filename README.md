1. Стефан Ангеловски, бр. на индекс 216091
2. ![Alt Text](https://i.imgur.com/4b9lg5F.png)
3. Цикломатската комплексност ја најдовме со тоа што се бројат сите затворени простори во CFG. Како и надворешниот простор, и таа комплексност ни е 11.
Може да ја потврдиме ако ги земеме сите if и for loops + 1.
4. Ке ни требаат пет тест случаи за Multiple Condition, еден случај што ке фрли Exception. Пример кога нема да пишеме Password, Email или да не постои корисник.
Вториот и третиот случај ке мора да пополниме Password, Email и корисник за да може да се влезе во следниот јазел. Во овој случај ке користиме име "Јован", кое во следниот јазел ке го искористиме како username.
Бидејки не користиме @, ке се префрлиме во следниот јазел каде што има проверка за големина и дали има мали букви. Ке биде точно и ке се одиме до крајот.
Третиот случај ке имаме постоечки Username, и затоа ке го искористиме истиот. Затоа ке ни треба и четврт случај за да направиме username so @ и да влеземе и во for циклусот каде ке правиме проверки дали нашиот емаил е валиден или не, како и username.
Тука ке го искористиме истиот случај како и уште еден со невалидни username и email.
5. if (user == null  user.getPassword() == null  user.getEmail() == null)
Во првиот случај ако user == null ке ни се исполни if условот
Тест случај два ке ни биде ако user != null, user.GetPassword() == null
Во третиот ако user != null, user.GetPassword() != null и user.GetEmail() == null
А и четврт ако user != null, user.GetPassword() != null и user.GetEmail() != null
