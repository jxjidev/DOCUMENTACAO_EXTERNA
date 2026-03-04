# Funcionamento

Quando a funcionalidade estiver ativa, ao executar o evento “Gerar versão para teste”, o sistema:&#x20;

1. Exibe um ícone de pendência de aprovação no card da demanda&#x20;
2. Dispara automaticamente um e-mail ao aprovador configurado&#x20;
3. Disponibiliza a solicitação no menu:&#x20;

<figure><img src="../.gitbook/assets/unknown (1).png" alt=""><figcaption></figcaption></figure>

Workflow → Aprovações

<figure><img src="../.gitbook/assets/unknown (2).png" alt=""><figcaption></figcaption></figure>

O aprovador terá as seguintes opções:&#x20;

* ✔ Aprovar – O transporte de cópia será liberado para importação no ambiente de Qualidade.&#x20;
* ❌ Reprovar – O transporte não será executado.&#x20;
* 🔒 Marcar como confiável – Permite definir que aquele card não necessitará de aprovação futura.

<figure><img src="../.gitbook/assets/unknown (3).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/unknown (4).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/unknown (5).png" alt=""><figcaption></figcaption></figure>

Após a aprovação:

* A Request de Cópia é automaticamente transportada&#x20;
* O fluxo da demanda segue normalmente no processo do QADevOps&#x20;
* O ambiente de Qualidade é atualizado conforme o procedimento padrão&#x20;
