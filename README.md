# PDV de Restaurante (Java)
apresentação técnica.

PDV desktop focado em operações de restaurante: mesas/comandas, pedidos, impressão de cupom e relatórios.

## Principais recursos
- Mesas/comandas, pedidos, categorias e itens.
- Caixa: abertura/fechamento, totalização e histórico.
- Impressão de cupom (ESC/POS) e relatórios (diário/por período).
- Backoffice básico: cadastro de produtos, preços e usuários.
- Banco: Derby (embedded) e compatibilidade com MySQL/PostgreSQL.

## Arquitetura (visão rápida)
- **Linguagem/UI:** Java (Swing).
- **Persistência:** ORM/JDBC.
- **Relatórios:** JasperReports.
- **Impressão:** ESC/POS (raw print/driver).
