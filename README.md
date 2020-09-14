# FromEats

##   서비스 소개

![picture1](./pictures/picture1.PNG)

![picture2](./pictures/picture2.PNG)

![picture3](./pictures/picture3.PNG)

![picture4](./pictures/picture4.PNG)

![picture5](./pictures/picture5.PNG)

![picture6](./pictures/picture6.PNG)

![picture7](./pictures/picture7.PNG)

![picture8](./pictures/picture8.PNG)

![picture9](./pictures/picture9.PNG)

![picture13](./pictures/picture13.PNG)

![picture14](./pictures/picture14.PNG)

![picture11](./pictures/picture11.PNG)

![picture12](./pictures/picture12.PNG)



## How to Run

### Sub1

```sh
cd sub1
pip install -r requirements.txt
python parse.py
python analyze.py
python visualize.py
```

### Sub 2

**Backend**

```sh
cd sub2/backend
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py initialize
python manage.py runserver
```

**Frontend**

```sh
cd sub2/frontend
npm install
npm run serve
```
