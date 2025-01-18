# Създайте локална директория и влезте в нея
mkdir github-exam
cd github-exam

# Инициализирайте локално Git хранилище
git init

# Създайте и добавете файловете
echo "The castle was quiet at night.
A lantern flickered in the tower.
A shadow moved behind the curtain.
Was someone watching?" > Pastel.txt

echo "The river flowed gently.
 It reflected the moonlight.
 Nearby, an owl hooted.
 The forest seemed alive." > Revir.txt

echo "The old book lay on the table.
Its pages were yellowed and torn.
A map fell out as it was opened.
Where could it lead?" > dooc.txt

# Добавете всички файлове за commit
git add .
