---
app: "Bem-Me-Ker"          # Entre as aspas escreve o nome da app
date: "22/07/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://apps.apple.com/pt/app/bem-me-ker/id1288638710"   # Entre as aspas escreve o endereço da app na loja
a11y_statement: "https://bemmeker-ipoporto.min-saude.pt/accessibility-declaration?tab=ios" # Entre as aspas escreve o URL da Declaração de Acessibilidade da App. A declaração da App está num URL público
owner: "IPO Porto"         # Entre as aspas escrever o nome do owner da app
seal: "Ouro"                          # Entre as aspas escreve Bronze, Prata ou Ouro
validity: "dd/mm/aaaa a dd/mm/aaaa" # Entre as aspas escreve data de início e data de fim no formato 31/12/1999 a 31/12/2000
status: "A aguardar correções da entidade" # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# Relatório de auditoria

Aplicação móvel: {{ page.app }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.app }}

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório App Bem-Me-Ker iOS](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="18082026_report.html">(18/08/2026). Relatório App Bem-Me-Ker iOS</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports Apps (v.1.0.0)</small></p>
