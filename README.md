# 🏨 Desafio Trilha .NET - Sistema de Hospedagem

Desafio de projeto da DIO Trilha .NET - Explorando a linguagem C#. Implementar um sistema de hospedagem em hotel com cálculo de diárias e validações.

## ✨ Objetivos do Desafio

- Implementar classe `Pessoa` (hóspede)
- Implementar classe `Suite` (acomodações)
- Implementar classe `Reserva` (relacionamento)
- Validar capacidade da suíte vs número de hóspedes
- Calcular valor das diárias com desconto de 10% para 10+ dias

## 🎯 Requisitos

1. ✅ Não permitir reserva com mais hóspedes que capacidade
2. ✅ Retornar quantidade total de hóspedes
3. ✅ Calcular valor da diária (dias × valor)
4. ✅ Aplicar 10% de desconto para reservas ≥ 10 dias

## 🛠️ Tecnologias

- C# 11
- .NET 6+
- Programação Orientada a Objetos

## 🚀 Como Executar

### Pré-requisitos
- .NET 6 ou superior
- Visual Studio 2022 ou VS Code com C# Dev Kit

### Instalação

```bash
git clone https://github.com/Denner-Dev/trilha-net-explorando-desafio.git
cd trilha-net-explorando-desafio
```

### Executar

```bash
dotnet run
```

## 📁 Estrutura

```
trilha-net-explorando-desafio/
├── Program.cs              # Programa principal
├── Models/
│   ├── Pessoa.cs          # Classe do hóspede
│   ├── Suite.cs           # Classe da suíte
│   └── Reserva.cs         # Classe da reserva
└── README.md              # Este arquivo
```

## 🔍 Classes Principais

### Pessoa
- Nome
- Sobrenome

### Suite
- TipoSuite (string)
- Capacidade (int)
- Valor (decimal)

### Reserva
- Lista de hóspedes
- Suite reservada
- Dias da reserva
- ObterQuantidadeHospedes()
- CalcularValorDiaria()

## 💡 Dicas de Implementação

1. Use validação no construtor da Reserva
2. Implemente a lógica de desconto em CalcularValorDiaria()
3. Lance exceção quando capacidade for ultrapassada

##  Licença

MIT
