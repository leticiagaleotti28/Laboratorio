<h1>Laboratório Médico</h1>

<h3>Descrição</h3>

Este sistema web, desenvolvido em Python e Django, funciona como um laboratório médico completo, permitindo a gestão de pacientes, agendamentos, exames e laudos. O sistema oferece uma interface intuitiva para pacientes e médicos, facilitando o gerenciamento de consultas e resultados de exames de forma organizada e eficiente.

<h3>Funcionalidades para Pacientes:</h3>

<ul>
<li>Autenticação e criação de perfil;</li>
<li>Agendamento de exames com seleção de data, hora e tipo de exame;</li>
<li>Visualização de exames agendados, incluindo data, hora, tipo de exame e status (pendente, realizado, cancelado);</li>
<li>Cancelamento ou remarcação de exames agendados;</li>
<li>Consulta de laudos de exames em formato PDF.</li>
</ul>

<h3>Funcionalidades para Médicos:</h3>

<ul>
<li>Autenticação e criação de perfil;</li>
<li>Visualização da agenda de pacientes com os exames agendados;</li>
<li>Registro dos resultados dos exames;</li>
<li>Anexação de laudos de exames em formato PDF;</li>
<li>Envio de notificações aos pacientes por email sobre a disponibilidade dos laudos.</li>
</ul>

<h3>Tecnologias Utilizadas:</h3>

<b>Linguagem de Programação:</b> Python<br>
<b>Framework Web:</b> Django<br>
<b>Banco de Dados:</b> SQLite (Opcional, outros bancos de dados compatíveis com Django podem ser utilizados)<br>

<h3>Bibliotecas Adicionais:</h3>
<b>django-rest-framework</b> (para criação de API REST)<br>
<b>django-filter</b> (para filtragem avançada de dados)<br>
<b>tempus-domi</b> (para envio de emails)<br>

<h3>Requisitos:</h3>
<ol>
<li>Conhecimento básico em Python e Django</li>
<li>Ambiente de desenvolvimento Python configurado</li>
<li>Banco de dados SQLite instalado e configurado (opcional)</li>
</ol>

<h3>Uso:</h3>

<h4>Pacientes:</h4>
<ol>
<li>Acesse o menu "Login" e cadastre-se ou faça login com sua conta existente.</li>
<li>No menu "Agendamentos", agende seus exames selecionando a data, hora e tipo de exame desejado.</li>
<li>Acesse o menu "Meus Exames" para visualizar seus exames agendados, cancelar ou remarcar um exame, e consultar seus laudos de exames.</li>
</ol>

<h4>Médicos:</h4>
<ol>
<li>Acesse o menu "Login" e faça login com sua conta existente.</li>
<li>No menu "Agenda", visualize a agenda de pacientes com os exames agendados.</li>
<li>Acesse o menu "Meus Pacientes" para visualizar a lista de pacientes e seus exames.</li>
<li>Selecione um paciente e um exame para registrar o resultado do exame e anexar o laudo em formato PDF.</li>
<li>O sistema enviará automaticamente uma notificação por email ao paciente informando a disponibilidade do laudo.</li>
<ol>

<h3>Observações:</h3>
Este é um projeto básico que pode ser expandido de acordo com suas necessidades específicas.
Utilize ferramentas de versionamento de código como o Git para gerenciar o desenvolvimento do projeto.
Mantenha o código documentado e organizado para facilitar a compreensão e futuras modificações.

<h3>Contribuições</h3>

Sinta-se à vontade para contribuir com o projeto sugerindo melhorias, reportando bugs ou criando novas funcionalidades.
