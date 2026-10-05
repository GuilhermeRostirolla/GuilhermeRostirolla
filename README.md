## Olá, eu sou o Guilherme

Analista de dados com foco em **Business Intelligence e automação de processos**, de Bento Gonçalves (RS).

Atuei na área de **Inovação e Transformação Digital do Grupo Bertolini**, onde levei processos que viviam em planilha e e-mail para dados estruturados e painéis de acompanhamento. Na prática, isso envolveu:

- **Organizar dados em SQL**, criando tabelas e consultas prontas para relatórios.
- **Buscar e tratar dados** com Python e Microsoft Fabric.
- **Criar dashboards** em Power BI, com DAX e Power Query.
- **Automatizar tarefas** com Power Apps e Power Automate, tirando etapas manuais do caminho.

Gosto de problemas em que o dado existe, mas ninguém confia nele ou consegue enxergá-lo. Meu trabalho é organizar a base, garantir a qualidade e entregar uma visão que ajude a decidir.

Estudante de Análise e Desenvolvimento de Sistemas na UCS.

<a href="https://www.linkedin.com/in/guilherme-rostirolla-923017263/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

## Projeto em destaque

### [Painel de Ideias · Python + SQL Server + Power BI](https://github.com/GuilhermeRostirolla/painel-ideias-powerbi)

Muitas empresas têm um programa em que os colaboradores enviam ideias de melhoria. O problema é que, depois de enviada, ninguém sabe direito o que acontece com a ideia: se está parada, se foi aprovada ou se gerou algum resultado.

Este painel resolve isso. Ele mostra, em poucos cliques, o caminho de cada ideia, do envio até a implantação, para 6 empresas e cerca de 870 ideias.

<a href="https://github.com/GuilhermeRostirolla/painel-ideias-powerbi"><img src="https://raw.githubusercontent.com/GuilhermeRostirolla/painel-ideias-powerbi/main/docs/img/painel.gif" alt="Tour pelo Painel de Ideias" width="720"></a>

**O que o painel responde**

- Quantas ideias chegam por mês e quantas viram melhoria de verdade.
- Em qual etapa as ideias ficam travadas e quais passaram do prazo.
- Quanto dinheiro foi investido e quanto as ideias devem trazer de retorno.
- Quantas pessoas participam e quais empresas estão perto da meta.

**Como eu construí**

1. **Criei os dados com Python.** O projeto é inspirado num caso real, mas os dados reais são sigilosos. Por isso, escrevi um programa que inventa as ideias, as pessoas e os valores, imitando como um programa de ideias funciona na prática: algumas ideias são aprovadas, outras reprovadas e outras voltam para ajuste.
2. **Organizei tudo em um banco SQL Server.** Separei os dados em tabelas fáceis de cruzar (ideias, pessoas, empresas, datas) e criei consultas prontas para o Power BI usar.
3. **Montei o painel no Power BI.** Criei as medidas em DAX e fiz cada empresa enxergar só os próprios dados.
4. **Garanti que tudo funciona.** Escrevi testes automáticos em Python que conferem se os dados gerados fazem sentido antes de chegarem ao painel.

**O que aprendi**

- Pensar primeiro na pergunta do negócio e só depois no gráfico.
- Organizar os dados antes de visualizar, para o painel ficar rápido e confiável.
- Criar dados fictícios realistas para mostrar um trabalho sem expor informação da empresa.
- Versionar um projeto de Power BI no Git, como se faz com código.

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/GuilhermeRostirolla/painel-ideias-powerbi/main/docs/img/visao_geral.png" alt="Visão geral do painel"></td>
    <td><img src="https://raw.githubusercontent.com/GuilhermeRostirolla/painel-ideias-powerbi/main/docs/img/financeiro.png" alt="Página financeira do painel"></td>
  </tr>
  <tr>
    <td align="center">Visão geral</td>
    <td align="center">Retorno financeiro</td>
  </tr>
</table>

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-117865?style=flat-square)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-1F4E5F?style=flat-square)
![Power Query](https://img.shields.io/badge/Power_Query-2F7A8C?style=flat-square)
![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## No que estou trabalhando

- Projeto no Microsoft Fabric que busca dados de projetos e tarefas por API e mostra o andamento em um painel Power BI.
- Aprofundando Python para análise de dados.
