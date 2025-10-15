# 🎮 Projeto Hermes - Arcade Sustentável

<div align="center">

![GitHub](https://img.shields.io/badge/GitHub-Organization-blue?style=for-the-badge&logo=github)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)

**Entretenimento + Sustentabilidade + Solidariedade**

</div>

---

## 📋 Sobre o Projeto

O **Projeto Hermes** é uma iniciativa inovadora que combina entretenimento, sustentabilidade e responsabilidade social. Desenvolvemos máquinas de arcade utilizando componentes reciclados, oferecendo aos alunos uma forma divertida de passar o tempo livre na escola, enquanto incentivamos a doação e a consciência ambiental.

## 🎯 Objetivos

- 🎮 **Entretenimento**: Proporcionar uma maior variedade de opções de lazer para os alunos durante intervalos e eventos escolares
- ♻️ **Sustentabilidade**: Reaproveitar recursos eletrônicos que estariam sem uso ou com mau funcionamento
- 🤝 **Solidariedade**: Arrecadar doações para os mais necessitados através de um sistema de créditos
- 🌱 **Educação Ambiental**: Incentivar a participação em projetos de reciclagem da instituição

## 🔧 Como Funciona

### Sistema de Créditos
Os alunos ganham créditos de duas formas:
- Fazendo doações para causas sociais
- Participando dos projetos de reciclagem da instituição

### Arquitetura do Sistema

O projeto utiliza componentes reciclados e reutilizados:

#### Hardware
- **Controles**: Botões padrões de arcade conectados à placa de um teclado antigo através de soldagem
- **Computador**: Notebook antigo para rodar os jogos e o servidor
- **Sistema de Autenticação**: Placa WeMos D1 conectada a:
  - Teclado matricial Arduino
  - Display LCD Arduino

#### Fluxo de Funcionamento

1. **Autenticação**: O aluno digita seu RM (Registro de Matrícula) no teclado
2. **Consulta**: A placa WeMos consulta a API do projeto para buscar os dados do aluno
3. **Exibição**: O display LCD mostra o nome do usuário e créditos disponíveis
4. **Confirmação**: Sistema pergunta "Você quer jogar? Sim:* Não:#"
   - **Sim**: Desconta um crédito via API e libera o jogo
   - **Não**: Limpa os dados e retorna ao início
5. **Atualização**: Após o jogo, atualiza os créditos do aluno

## 🛠️ Tecnologias Utilizadas

- **Hardware**: Arduino, WeMos D1, componentes reciclados
- **Software**: API REST para gerenciamento de usuários e créditos
- **Interface**: Display LCD 16x2, Teclado Matricial

## 📂 Estrutura do Repositório

Este é o repositório `.github` da organização Hermes, contendo:
- Perfil da organização
- Documentação geral do projeto
- Templates e workflows

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/MTSmalow" title="Github do Eduardo">
        <img src="https://avatars.githubusercontent.com/u/134291030?v=4" width="100px;" alt="Foto do Eduardo no GitHub"/><br>
        <sub>
          <b>Eduardo</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/RaffaEarth" title="Github do Rafael">
        <img src="https://avatars.githubusercontent.com/u/133674172?v=4" width="100px;" alt="Foto do Rafael no Github"/><br>
        <sub>
          <b>Rafael</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 🚀 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto é de código aberto e está disponível para uso educacional.

## 📞 Contato

Para mais informações sobre o projeto, entre em contato com a equipe Hermes através da organização no GitHub.

---

<div align="center">

♻️ Reciclando o Passado | 🎮 Criando o Futuro | 🤝 Ajudando o Próximo

</div>
