# Configurações

#### **Tipo de integração externa**

* Define a ferramenta externa utilizada
* Valor suportado:
  * Service Now

#### **Email para comunicação**

* Recebe notificações da integração
* Permite múltiplos e-mails (separados por vírgula)

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

#### **Desabilitar criação de change**

* Quando ativado:
  * Impede criação automática de Changes
* Quando desativado (padrão):
  * Changes são criadas automaticamente

#### **Usuário de integração**

* Login para autenticação na API do ServiceNow
* Deve ter permissões para:
  * Criar Changes
  * Atualizar Changes e Tasks

#### **Senha de integração**

* Senha do usuário de integração
* Usada na autentação da API
* Deve ser mantida em segurança

#### **Criar mudança**

* Define endpoint/configuração para:
  * Criar Change no ServiceNow

#### **Criar task**

* Define endpoint/configuração para:
  * Criar Task vinculada à Change

#### **Alterar status da change**

* Define como atualizar o status da Change
* Permite sincronizar o ciclo de vida entre sistemas

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### **Intervalo de monitoramento da mudança (minutos)**

* Define frequência de verificação do status da Change
* Valores:
  * 0 → Monitoramento desativado ou por evento
  * > 0 → Verificação periódica

#### **Buscar usuários aprovadores**

*   Define consulta/configuração para:

    * Buscar aprovadores no ServiceNow



<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>
