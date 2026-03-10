📌 Descrição
Este projeto demonstra como estruturar e executar testes automatizados em aplicações .NET, explorando dois frameworks populares:
- MSTest (framework oficial da Microsoft)
- xUnit (framework moderno e flexível, amplamente usado pela comunidade)

🛠️ Tecnologias Utilizadas
- C# 100%
- .NET SDK (versão 6 ou superior)
- Visual Studio 2022 / VS Code
- MSTest
- xUnit

📂 Estrutura do Projeto
Testes/
├── .vs/ProjetoTeste/          # Configurações do Visual Studio
├── ProjetoTeste/              # Projeto principal
├── TestTesteMSTEST/           # Projeto de testes com MSTest
├── TesteXunit/                # Projeto de testes com xUnit
└── ProjetoTeste.sln           # Solution principal



🚀 Como Executar
- Clone o repositório:
git clone https://github.com/EmmanuelTorresBackEnd/Testes.git
- Restaure pacotes:
dotnet restore
- Execute os testes:
dotnet test



📖 Exemplos de Uso
MSTest
[TestClass]
public class CalculadoraTests
{
    [TestMethod]
    public void Soma_DeveRetornarResultadoCorreto()
    {
        var resultado = Calculadora.Somar(2, 3);
        Assert.AreEqual(5, resultado);
    }
}


xUnit
public class CalculadoraTests
{
    [Fact]
    public void Soma_DeveRetornarResultadoCorreto()
    {
        var resultado = Calculadora.Somar(2, 3);
        Assert.Equal(5, resultado);
    }
}



📌 Status
- ✅ Estrutura inicial pronta
- ✅ Testes implementados em MSTest e xUnit
- 🚀 Próximos passos: adicionar mais cenários de teste e explorar mocks/stubs

📞 Contato
Emmanuel Torres - 8Tech
📧 emmanueltorres21@live.com
📱 +55 (83) 98190-1739
📍 Campina Grande, PB - Brasil


