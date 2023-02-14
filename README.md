# test_script

build:
docker build -t pythonimage .

run:
docker run --entrypoint="python" pythonimage "cronjob.py"
