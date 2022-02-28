Привіт усім небайдужим хто хоче допомогти атаці на іт рф (і не зашкодити укр інету), ми зробили гайд як це зробити за можливістю поширюйте 
Гайд як ддсоти не зі свого компа 
1. Заходимо на cloud.digitalocean.com
2. Якщо ви студент, і у вас є github educational pack (https://education.github.com/pack), то логінімось через github в digital ocean и можемо як студент отримати просто так 50 $. https://www.digitalocean.com/community/questions/github-student-pack-2 (тут є деталі як це робити) або 100$ по реферальному посиланню https://www.digitalocean.com/try/developer-brand-r?utm_campaign=emea_brand_kw_en_cpc&utm_adgroup=digitalocean_exact_bmm&_keyword=digitalocean&_device=c&_adposition=&utm_content=conversion&utm_medium=cpc&utm_source=google&gclid=CjwKCAiAvOeQBhBkEiwAxutUVP7vmbhFnUYLT09ogzQy3oa3rctgAdSO5jqEMezBitn-McGJJ8OiLBoCw5YQAvD_BwE

Інакше просто реєструйте звичайний аккаунт, прив*язуйте карту, де зазвичай не більше 100 грн, щоб не знало багато (один сервер коштує 5 долларі)
3. Зверху у панелі  жмакаємо Create -> Droplets. 
![приклад](https://github.com/Eragoo/digital-ocean-memes-for-russians/blob/main/Screenshot%202022-02-27%20at%2017.09.20.png)


Обираємо Marketplace -> Dockerза основу, CPU Options - regular Inter with SSD, той що за солодкі 5$ за місяць. Обираємо локацію, є сенс брати щось в Європі так як буде менше затримка з рашкою. Обираємо на свій смак.  Коли реєструємо обираємо захід по root password.  Тицяємо зелену кнопку Create Droplet






4. Чекаємо як цей  сервер створиться (ім*я у кожного різне)
Буде отак:
5. Заходимо в дроплет і тицяємо на Console:

6. Буде щось таке:
7. Далі виконуємо команду git clone https://github.com/almerico/bombardier.git

8.Переходимо в папку проекту за допомогою команди: cd bombardier  
Далі запускаємо атаку на всі ресурси з файлу resources.txt що знаходиться в директорії
./run_all_docker.sh

Той файл можна редагувати самостійно, з консолі, для цього можна гуглити як користуватись nano.
Вітаю, ви частина команди кібер партизанів!
