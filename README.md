# seokjunHwang.github.io

이 프로젝트는 github blog를 html로 구현하는 것입니다.

See [Demo](https://seokjunhwang.github.io/)

## 설명

github flavored markdown은 수식표현을 제공합니다.

예를들면,

### Binet's Formula

$F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}$

```math
F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}
```



## 설치하는 법

```shell
$ git clone {addr}
$ cd {repo name}
$ pip install -r requirements.txt
```

## 시작하는 법

```shell
$ python main.py
```

## 기능 설명

## 정답확인하는 함수

```python
def checker(answer: int, guess: int) -> bool:
	if guess==answer:
		print('correct!')
		retrun True
	else:
		print('Wrong!')
		return False
```

## 더 많은 정보

- [google](https://www.google.com/)

