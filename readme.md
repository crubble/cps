
# Projeto de Criptografia e Protocolos de Segurança

## Private Set Intersection

### Artigo

Disponível [aqui](https://link.springer.com/chapter/10.1007/11535218_15#preview), [aqui](https://bitblaze.cs.berkeley.edu/papers/set-tech-full.pdf) e [aqui](https://iacr.org/archive/crypto2005/36210235/36210235.pdf).

### Ambiente de programação

Acho melhor usarmos [jupyter](https://jupyter.org/install) como em introdução à programação, mas se quizerem podemos usar ficheiros normais de python. O [vscode](https://code.visualstudio.com) também tem uma [extensão de jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) se preferirem ao browser.

### Instalar as packages usadas

Se usarem anaconda corram isto no terminal:
`conda install nympy phe gmpy2`

Se tiverem só o python instalado corram isto:
`pip install numpy phe gmpy2`

### Usar o github

Instalar o [git](https://git-scm.com/downloads).

Primeira vez:
1. `git clone https://github.com/crubble/cps.git`
1. `cd cps`
1. `git config --global user.name "Your Name"`
1. `git config --global user.email "you@example.com"`

Vezes seguintes: `git pull`

Para fazer alterações:
1. `git add .`
1. `git commit -m "_escrever mensagem aqui_"`
1. `git push`

Para ver o estado da coisa:
`git status`

### Documentação das packages usadas

Polynomials:
https://numpy.org/doc/stable/reference/routines.polynomials.html

Pallier:
https://github.com/data61/python-paillier/blob/master/docs/usage.rst
