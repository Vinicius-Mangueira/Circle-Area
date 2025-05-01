# Calculadora de Área do Círculo / Circle Area Calculator

Um pequeno projeto em **Python 3** criado durante o curso da Cod3r. Este repositório demonstra passo a passo como calcular a área de um círculo a partir do raio fornecido pelo usuário.
A simple Python 3 project from the Cod3r course. This repository walks through how to calculate the area of a circle based on a user-provided radius.

---

## 📖 Sobre / About

**Português:**
Este é um exercício prático do curso de Python 3 da Cod3r. O objetivo é:

- Apresentar versões evolutivas de um mesmo script, ilustrando boas práticas de refatoração.  
- Ensinar como ler entrada do usuário, validar dados e usar funções do módulo `math`.  
- Demonstrar como organizar seu projeto e usar o Git para versionar código.

**English:**
This is a hands-on exercise from Cod3r's Python 3 course. The goals are:

- Showcase multiple script versions illustrating best practices in refactoring.  
- Teach user input handling, data validation, and use of the `math` module.  
- Demonstrate project organization and Git workflow.

---

## ✨ Funcionalidades / Features

**Português:**
- **Várias versões:** cada arquivo `area_circulo_vX.py` mostra uma melhora incremental na estrutura do código.  
- **Função reutilizável:** `calculate_circle_area(radius: float) → float`.  
- **Validação de entrada:** garante que o usuário informe um raio numérico e não-negativo.  
- **Saída formatada:** exibe a área com casas decimais ajustadas para melhor leitura.

**English:**
- **Multiple Versions:** each `area_circulo_vX.py` file demonstrates incremental code improvements.  
- **Reusable Function:** `calculate_circle_area(radius: float) → float`.  
- **Input Validation:** ensures the user provides a numeric, non-negative radius.  
- **Formatted Output:** displays the area with a user-friendly number of decimal places.

---

## 🗂️ Estrutura do Repositório / Project Structure

```plaintext
.
├── LICENSE
├── README.md
├── .gitignore
└── Versions_circle_area
    ├── area_circulo_v1.py     # Versão inicial: cálculo direto / Initial version: direct calculation
    ├── area_circulo_v2.py     # Encapsula em função / Encapsulates logic in a function
    ├── …                       # Passos intermediários de refatoração / Intermediate refactoring steps
    └── area_circulo_v10.py    # Versão final: validação e formatação / Final version: validation and formatting
```

---

## 🚀 Como Usar / Usage

**Português:**
1. **Clone este repositório**  
   ```bash
   git clone https://github.com/Vinicius-Mangueira/Circle-Area.git
   cd Circle-Area/Versions_circle_area
   ```
2. **Execute a versão desejada**  
   ```bash
   python area_circulo_v10.py
   ```
3. **Informe o raio** quando solicitado, por exemplo `5`, e veja o resultado:
   ```text
   Enter the circle's radius: 5
   The area is: 78.54
   ```

**English:**
1. **Clone this repository**  
   ```bash
   git clone https://github.com/Vinicius-Mangueira/Circle-Area.git
   cd Circle-Area/Versions_circle_area
   ```
2. **Run your desired version**  
   ```bash
   python area_circulo_v10.py
   ```
3. **Enter the radius** when prompted (e.g., `5`) and view the output:
   ```text
   Enter the circle's radius: 5
   The area is: 78.54
   ```

---

## 📝 .gitignore

**Português:**
Este projeto já ignora automaticamente arquivos compilados e pastas temporárias. Exemplo de entrada no `.gitignore`:

```
__pycache__/
*.pyc
```

**English:**
This project already excludes compiled files and temporary folders. Example `.gitignore` entries:

```
__pycache__/
*.pyc
```

---

## 🤝 Contribuição / Contributing

**Português:**
1. Fork este repositório  
2. Crie sua branch de feature:  
   ```bash
   git checkout -b feature/nova-ideia
   ```  
3. Faça commit das suas alterações:  
   ```bash
   git commit -m "Descrição da mudança"
   ```  
4. Abra um Pull Request.

**English:**
1. Fork this repository  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/my-new-feature
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Description of changes"
   ```  
4. Open a Pull Request.

---

## 📄 Licença / License

**Português:**
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

**English:**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 👤 Autor / Author

**Português:**
Projeto desenvolvido por **Vinícius Mangueira** durante o curso de Python 3 da Cod3r.

**English:**
Project developed by **Vinícius Mangueira** as part of Cod3r's Python 3 course.

