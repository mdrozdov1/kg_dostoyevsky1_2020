# kg_dostoyevsky1_2020
#### Python script to test strings for one-to-one mapping (isomorphism)


#### Implementation method 1 (with Python installed)

Clone repo:
```
git clone https://github.com/dostoyevsky1/kg_dostoyevsky1_2020.git
```

Cd into repo:
```
cd kg_dostoyevsky1_2020/
```

Run script:
```
python3 main.py [arg1] [arg2]
```


#### Implementation method 2 (with Docker installed)
#### Docker image: https://hub.docker.com/repository/docker/dostoyevsky/isomorphism

Pull image:
```
docker pull -a dostoyevsky/isomorphism
```

Run container:
```
docker run -it dostoyevsky/isomorphism:1.0 /bin/bash
```

Run script:
```
python3 main.py [arg1] [arg2]
```

OR

Run container + script:
```
docker run -it dostoyevsky/isomorphism:1.0 python main.py [arg1] [arg2]
```

#### Examples:

INPUT:
```
python main.py bar foo
```
OUTPUT:
```
False
```

INPUT:
```
python main.py 123 321
```
OUTPUT:
```
True
```
