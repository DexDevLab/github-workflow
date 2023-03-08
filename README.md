<h1 align="center">github-workflow</h1>
<p align=center><i align="center">Repositório para testes de github workflow e scripts de automação.</i></p>

<br>

<div align="center">

<a href=""><img src="https://snyk.io/test/github/dexdevlab/github-workflow/badge.svg?style=plastic" height="20" alt="Snyk"></a>

<a href=""><img src="https://img.shields.io/github/languages/code-size/dexdevlab/github-workflow?style=plastic" height="20" alt="CodeSize"></a>
<a href=""><img src="https://img.shields.io/github/repo-size/dexdevlab/github-workflow?style=plastic" height="20" alt="RepoSize"></a>

<!-- <a href="https://github.com/dexdevlab/ebac-engenheiro-frontend/graphs/contributors"><img src="https://img.shields.io/github/contributors/dexdevlab/ebac-engenheiro-frontend?style=plastic" height="20" alt="Contributors"></a> -->

<!--
<a href="https://github.com/dexdevlab/ebac-engenheiro-frontend/fork"><img src="https://img.shields.io/github/forks/dexdevlab/ebac-engenheiro-frontend?style=plastic" height="20" alt="Fork"></a>  -->

<a href=""><img src="https://img.shields.io/github/last-commit/dexdevlab/github-workflow?style=plastic" height="20" alt="LastCommit"></a>
<a href=""><img src="https://img.shields.io/badge/version-1.0.0-005bff?style=plastic" height="20" alt="Version"></a>
<a href="https://github.com/dexdevlab/github-workflow/blob/main/LICENSE"><img src="https://img.shields.io/github/license/dexdevlab/github-workflow?&style=plastic" height="20" alt="License"></a>

|| [Conteúdo](#section-conteudo) || [Notas de versão](#section-changelog) || [Autores](#section-autores) ||

|| [Contato](#section-contato) || [Licença](#section-licenca) ||

</div>

<hr>

<a name="section-conteudo">

## Conteúdo

</a>

Este repositório serve como um sandbox para testes com workflows (Github Actions), de forma que é possível testar os mais diferentes scripts de automação, possibilitando fácil adaptação e customização para atender necessidades específicas.

### Templates

Este repositório também conta com alguns templates que podem ser facilmente utilizados, podendo ser acessados em ['templates'](https://github.com/dexdevlab/github-workflow/blob/main/templates):

'tag' - Permite criar uma tag automaticamente, de acordo com o critério especificado. No template, a ação ocorre em cada 'push' realizado no branch 'main'. Requer um arquivo [`package.json`](https://github.com/dexdevlab/github-workflow/blob/main/package.json) para funcionar corretamente.

'release' - Permite criar uma release automaticamente, de acordo com o critério especificado. No template, a ação ocorre em cada 'push' marcado com uma tag que comece com 'v'.

'changelog-release' - Gera um changelog para cada release realizado.

'tag-release' - Cria automaticamente uma Tag, e então uma release, respeitando Versionamento Semântico, de acordo com o critério especificado. No template, a ação ocorre em cada 'push' realizado no branch 'main', e ignora automaticamente quaisquer versões do projeto que possuam o sufixo '-beta'. Requer um arquivo [`package.json`](https://github.com/dexdevlab/github-workflow/blob/main/package.json) para funcionar corretamente. Em caso de se utilizar outro sufixo indicador de versão como excludente, é possível substituir a variável `SUFFIX` por qualquer outro valor.

<hr>

<a name="section-changelog">

## Notas de versão

</a>

### v0.1.40-230308-beta

- Teste de aplicação da variável de ambiente 'SUFFIX' para regras de exclusão

### v0.1.39-230308-beta

- Teste de aplicação da variável de ambiente 'SUFFIX' para regras de exclusão

### v0.1.38-230308-beta

- Restruturação da localização dos templates
- Criado arquivo README
- Criado arquivo README para instruções para o template 'tag+release'
- Teste de aplicação da variável de ambiente 'SUFFIX' para regras de exclusão

### v0.1.37-230308

- Update tag.yml
- Auto release and tag template removed

### v0.1.36-230308

- Update tag.yml

### v0.1.35-230308

- Update tag.yml

### v0.1.34-230308

- Update tag.yml

### v0.1.33-230308

- Update tag.yml

### v0.1.32-230308

- Update package.json

### v0.1.31-230308

- Update tag.yml

### v0.1.30-230308

- Deployment test

### v0.1.29-230308

- Format YML files
- Update tag.yml

### v0.1.28-230308

- Update tag.yml

### v0.1.27-230308

- Update release.yml

### v0.1.26-230308

- Update release.yml

### v0.1.25-230308

- Update release.yml

### v0.1.24-230308

- Update release.yml

### v0.1.23-230308

- Update release.yml

### v0.1.22-230308

- Update release.yml

### v0.1.21-230308

- Deployment test with semver timestamp suffix

### v0.1.20-230308

- Deploy test with workflow in a normal commit

### v0.1.19-230308

- Beta deployment test for workflows

### v0.1.18-230308

- Update release.yml

### v0.1.17-230308

- Update release.yml
- Update tag.yml

### v0.1.16-230308

- Update release.yml

### v0.1.15-230308

- Update release.yml

### v0.1.14-230308

- Update release.yml

### v0.1.13-230308

- Update release.yml
- Update tag.yml

### v0.1.12-230308

- Update release.yml
- Update tag.yml

### v0.1.11-230308

- Update release.yml

### v0.1.10-230308

- Added sequencial workflow parameters
- Added sequencial workflow for tag + release
- Package.json update

### v0.1.9-230308

- v0.1.9

### v0.1.8-230308

- Update package.json
- Update tag.yml

### v0.1.7-230308

- Update tag.yml

### v0.1.6-230308

- Update tag.yml

### v0.1.5-230308

- Workflow Tag test
- Workflow templates folder created
- Package.json createdl

### v0.1.4-230308

- Update release.yml

### v0.1.3-230308

- Update release.yml

### v0.1.2-230308

- Update release.yml

### v0.1.1-230308

- Update release.yml

### v0.1.0-230308

- Criação do repositório

<hr>

<a name="section-autores">

## Autores

</a>

<a href="https://github.com/dexdevlab/ebac-engenheiro-frontend/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=dexdevlab/ebac-engenheiro-frontend" />
</a>

<hr>

<a name="section-contato">

## Contato

</a>

Se você gostou desse projeto, nos dê uma <a href="https://github.com/dexdevlab/ebac-engenheiro-frontend" data-icon="octicon-star" aria-label="Star dexdevlab/ebac-engenheiro-frontend on GitHub">estrela</a>. <br>
Para contato, envie um email a: <a href="mailto:dex.houshi@hotmail.com">dex.houshi@hotmail.com</a>

<hr>

<a name="section-licenca">

## Licença

</a>

Licenciado sob a [MIT License](https://github.com/dexdevlab/ebac-engenheiro-frontend/blob/master/LICENSE).
