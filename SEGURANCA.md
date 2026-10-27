# Revisão de segurança — Refúgio da Família Koch

- Política CSP via meta tag para limitar scripts, conexões, objetos, frames e origens de imagens.
- Links externos em nova aba com `noopener noreferrer`.
- Política de referenciador para limitar dados enviados a sites externos.
- Correção da abertura duplicada do HTML da página de contato.
- Nenhuma senha ou chave de API foi identificada nos HTMLs.

## Limitações
O site usa JavaScript e CSS embutidos, por isso a CSP ainda permite `unsafe-inline` nesses dois tipos. Isso é uma melhoria parcial, não uma auditoria de segurança completa. A política por meta tag não substitui cabeçalhos HTTP e não permite configurar todas as diretivas, como `frame-ancestors`. O GitHub Pages gerencia HTTPS.

Antes de publicar, teste todas as páginas, o menu no celular, as galerias, o botão de copiar telefone e os links de reserva.

Ative autenticação de dois fatores na conta GitHub. Não inclua senhas, códigos de acesso das casas ou dados de hóspedes no repositório público.
