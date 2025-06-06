# Habilitar validação de objetos que alteram tabelas

Ao habilitar essa funcionalidade, o sistema passa a realizar uma verificação específica para objetos que **criam** ou **alteram** tabelas no banco de dados. Quando essa condição é identificada, o sistema automaticamente **classifica a demanda como geradora de débito técnico**.

Como consequência, a demanda exigirá um fluxo adicional de **aprovação específica**, garantindo que alterações estruturais em tabelas sejam devidamente avaliadas antes de sua implantação.

Essa validação tem como objetivo fortalecer o controle sobre mudanças críticas na base de dados, prevenindo impactos negativos em ambientes produtivos e promovendo boas práticas de governança técnica.



Exemplo:

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
