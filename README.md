Aqui está um **README profissional** para o seu projeto 🚀

---

# 🌍 Global Exchange - Conversor de Moedas

Projeto desenvolvido como parte da disciplina **Interação Humano-Computador (IHC) & UX**, com foco na criação de uma aplicação de console que entrega **uma experiência de usuário intuitiva, robusta e agradável**.

---

## 📌 Sobre o Projeto

O **Global Exchange** é um conversor de moedas que transforma valores em reais (R$) para dólares (USD), simulando um sistema financeiro real com:

* Feedback visual de processamento
* Tratamento de erros
* Interface organizada e amigável

---

## ⚙️ Funcionalidades

✅ Conversão de Real para Dólar
✅ Simulação de conexão com sistema externo
✅ Exibição de status em tempo real
✅ Tratamento de erros de entrada
✅ Resultado formatado com precisão

---

## 🧠 Heurísticas de UX Aplicadas

### 👁️ 1. Visibilidade do Status do Sistema

O sistema informa claramente o que está acontecendo:

```
[SISTEMA]: Conectando ao Banco Central...
[SISTEMA]: Calculando taxas...
```

➡️ Isso reduz ansiedade do usuário e melhora a percepção de performance.

---

### 🛡️ 2. Prevenção de Erros

Uso de `try-catch` para evitar que o sistema quebre:

```csharp
catch (Exception)
{
    Console.WriteLine("Entrada inválida! Use apenas números.");
}
```

➡️ O sistema continua funcionando mesmo com erro do usuário.

---

### 🎨 3. Estética e Design Minimalista

Uso de cores e organização visual:

* 🟡 Título em destaque
* 🟢 Resultado final
* 🔴 Mensagens de erro

➡️ Interface simples, limpa e fácil de entender.

---

## 💻 Tecnologias Utilizadas

* C#
* .NET (Console Application)
* Visual Studio Code

---

## 📂 Estrutura do Projeto

```
📁 ConversorExpert
 ┣ 📄 Program.cs
 ┣ 📄 ConversorExpert.csproj
📄 README.md
📄 evidencia-final.png
```

---

## 📸 Evidência

Adicione aqui o print do sistema funcionando:

<img width="1012" height="726" alt="image" src="https://github.com/user-attachments/assets/9da13760-ce3a-4ed0-8364-ae3ae717cd56" />


---

## 🚀 Como Executar

```bash
cd LabDotnet
dotnet new console -n ConversorExpert
cd ConversorExpert
dotnet run
```

---

## 📊 Exemplo de Uso

```
Digite o valor em REAIS (R$): 100
Digite a cotação do DÓLAR hoje: 5,00

[SISTEMA]: Conectando ao Banco Central...
[SISTEMA]: Calculando taxas...

VALOR CONVERTIDO: $ 20.00 (Dólares)
```

---

## 🧾 Reflexão Final

> Após passar por essas 4 missões, minha visão sobre "apenas escrever código" mudou completamente.
>
> Antes, o foco era apenas fazer o sistema funcionar. Agora, percebo que **a experiência do usuário é tão importante quanto a lógica do código**.
>
> Pequenos detalhes como mensagens claras, feedback visual e tratamento de erros fazem toda a diferença, tornando o sistema mais profissional, confiável e agradável de usar.

---

## ✅ Checklist de Sucesso

* [x] Uso de `Thread.Sleep` para simular processamento
* [x] Uso de `try-catch` para evitar falhas
* [x] Formatação com duas casas decimais (`:F2`)
* [x] Interface organizada e amigável

---

## 💡 Evolução Futura

🔌 Integração com API de cotação em tempo real
📊 Suporte a múltiplas moedas
🖥️ Interface gráfica (GUI)

---

✨ **Projeto finalizado com foco em UX + Código de Qualidade!**
