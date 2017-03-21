=================
CHECK-IN Commiter
=================

Commita presença no repositório de chamada.


Uso
===

Configuração inicial
--------------------

Faça a configuração do git conforme os comandos a baixo, informando seu nome, e-mail da UNIVILLE e criando o comando do git:

.. code-block:: sh

  git config --global user.name 'Nome Completo'
  git config --global user.email 'usuario@univille.br'

  git config --global alias.presenca '!curl -sSL https://github.com/eduardoklosowski/check-in-commiter/raw/master/check-in | bash'


Commitando presença
-------------------

Para commitar a presença, execute:

.. code-block:: sh

  git presenca
