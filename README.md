# GymGuide360

* Run application(Before  run add key in .env file)
```bash
streamlit run src/app.py
```

* Run on docker
```bash
docker build -f ./Dockerfile . -t gymbot:1.0.0
```

* Start Container
```bash
docker run -it -d -p 8501:8501 --name gym_guide gymbot:1.0.0
```