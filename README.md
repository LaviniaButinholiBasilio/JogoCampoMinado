# 💣 Campo Minado (Python - Terminal)

![Feito com Python](https://img.shields.io/badge/feito%20com-Python-FFC0CB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-concluído-FFC0CB)
![Licença](https://img.shields.io/badge/licença-Livre-FFC0CB)
![Autoria](https://img.shields.io/badge/feito%20por-Lavínia%20Butinholi%20Basílio-FFC0CB)

---

## 📖 Descrição
Este projeto implementa o clássico **Campo Minado** em **Python**, totalmente jogável no terminal.  
O usuário pode escolher o tamanho do tabuleiro e a quantidade de minas, abrindo células ou marcando possíveis minas.  
O jogo termina quando o usuário abre uma mina (derrota) ou quando abre todas as células sem minas (vitória).

---

## ⚙️ Funcionalidades
- 🧩 Criação dinâmica do tabuleiro (NxN)  
- 💣 Configuração de quantidade de minas  
- 🔹 Abrir células, marcar ou desmarcar minas  
- ✅ Verificação de vitória ou derrota  
- 💬 Interface simples via terminal  

---

## 🧠 Estrutura do Código
| Função | Descrição |
|--------|------------|
| `criar_tabuleiro(linhas, bombas)` | Cria uma matriz NxN com bombas aleatórias e contagem de minas próximas |
| `imprimir_tabuleiro(tabuleiro, mostrar_minas=False)` | Exibe o tabuleiro no terminal, opcionalmente mostrando todas as minas |
| `abrir_celula(tabuleiro, x, y)` | Abre a célula selecionada, retorna False se for uma mina |
| `marcar_mina(tabuleiro, x, y)` | Marca a célula como mina suspeita |
| `desmarcar_mina(tabuleiro, x, y)` | Desmarca uma célula previamente marcada |
| `contar_minas_proximas(tabuleiro, x, y)` | Conta minas adjacentes a uma célula |

---

## 👩‍💻 Autor

**Lavínia Butinholi Basílio**  
Projeto criado para fins educacionais.

## 🪶 Licença

Este projeto é de uso livre para fins educacionais.  


## 🎮 Como Jogar

1. Escolha o tamanho do tabuleiro.  
2. Escolha o número de minas.  
3. Abra células ou marque minas.  
4. O jogo termina em vitória ou derrota.


## 🚀 Como Executar

### 1️⃣ Pré-requisitos
- Ter o **Python 3** instalado no sistema

### 2️⃣ Clonar o repositório
```bash
git clone https://github.com/seuusuario/campo-minado.git
cd campo-minado
python campo_minado.py


