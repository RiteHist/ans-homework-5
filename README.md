# ans-homework-5

Ссылка на [репозиторий с vector-role](https://github.com/RiteHist/vector-role)

## Molecule

Ссылка на [тег репозитория с настроенным сценарием для Molecule](https://github.com/RiteHist/vector-role/releases/tag/1.1)

Для выполнения задания были созданы файлы [converge.yml](https://github.com/RiteHist/vector-role/blob/main/molecule/default/converge.yml), [molecule.yml](https://github.com/RiteHist/vector-role/blob/main/molecule/default/molecule.yml) и [verify.yml](https://github.com/RiteHist/vector-role/blob/main/molecule/default/verify.yml) внутри каталога [default сценария](https://github.com/RiteHist/vector-role/tree/main/molecule/default)

Выполнение play в контейнерах:

![alt text](https://github.com/RiteHist/ans-homework-5/blob/main/media/1.PNG?raw=true)

Проверка play на идемпотентность:

![alt text](https://github.com/RiteHist/ans-homework-5/blob/main/media/2.PNG?raw=true)

Выполнение проверок из файла verify.yml:

![alt text](https://github.com/RiteHist/ans-homework-5/blob/main/media/3.PNG?raw=true)

## Tox

Ссылка на [тег репозитория с настроенным сценарием для Tox](https://github.com/RiteHist/vector-role/releases/tag/1.2)

Для выполнения задания был создан сценарий [tox-light](https://github.com/RiteHist/vector-role/tree/main/molecule/tox-light) с файлами [converge.yml](https://github.com/RiteHist/vector-role/blob/main/molecule/tox-light/converge.yml) и [molecule.yml](https://github.com/RiteHist/vector-role/blob/main/molecule/tox-light/molecule.yml)

Результаты запуска Tox с настроенным сценарием:

![alt text](https://github.com/RiteHist/ans-homework-5/blob/main/media/4.PNG?raw=true)

