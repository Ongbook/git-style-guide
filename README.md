<img src="https://central.ongbook.org/img/ongbook.png" width="127px" height="127px" align="left"/>

# Git Style Guide

Git styleguide sugerido por nós da **Ongbook**

<br>

<h3><a id="Branchs_0"></a>Branchs</h3>
<ul>
<li><strong>develop:</strong> versão que contém todas as novas features desenvolvidas (onde todo o ciclo de teste e validação foram feitos), não deve conter desenvolvimentos não aprovados e desenvolvimentos incompletos, ou seja, tudo que está preparado e aprovado para ir pra próxima release em produção. caso tenha algum hotfix, o conteúdo do hotfix também fica disponível em develop</li>
<li><strong>master:</strong> última versão estável, contém todos os recursos entregues em produção, caso tenha algum hotfix, o conteúdo do hotfix também fica disponível em master</li>
<li><strong>feature/xxxx:</strong> uma branch temporária que contém a implementação candidata na próxima release, onde seu ciclo de vida fica limitado à sua aprovação e validação, na sua finalização deve ir para o branch develop</li>
<li><strong>bugfix/xxxx:</strong> uma branch temporária que contém uma correção que não é emergencial e pode ser levada para a próxima release. seu ciclo de vida é semelhante ao feature, somente muda o nome por respeito à nomenclatura da classificação da implementação</li>
<li><strong>hotfix/xxxx:</strong> uma branch temporária que contém uma correção que é emergencial, devido à sua operação, deve ser definido por toda a equipe se a correção é uma hotfix. Seu ciclo de vida termina na validação da correção do erro e seu conteúdo deve ir para master e develop.</li>
</ul>
<h3><a id="Commits_7"></a>Commits</h3>
<ul>
<li><strong>feat:</strong> nova feature</li>
<li><strong>fix:</strong> correção de código</li>
<li><strong>docs:</strong> melhoria de comentário de código ou edição da parte de documentação da sua base de código;</li>
<li><strong>style:</strong> melhorias de formatação de texto, mudança de estilo de codificação;</li>
<li><strong>refactor:</strong> uma vez trabalhando com boa cobertura de teste ou não (o risco é por sua conta), esse commit é quando for apenas refatorar seu código;</li>
<li><strong>perf:</strong> quase a mesma pegada do refactor mas esse ajuste resulta em maior performance da solução;</li>
<li><strong>test:</strong> inclusão ou manuntenção de testes do software;</li>
<li><strong>chore:</strong> se o que alterou não está associado a algum listado acima, utilize ele para classificar.</li>
<li><strong>ci:</strong> para alterações no script de integração contínua</li>
</ul>

# Tabela de Conteúdo

1. [Branches](#branches)
2. [Commits](#commits)
  1. [Mensagens](#messages)
3. [Merging](#merging)
4. [Misc.](#misc)

