# Atividade4_DML_DELETE

```SQL
/* Para concluir esse exercicio tive que desativar a opção 
de "Habilitar verificação de chaves estrangeiras" */
```

### Instrução 1
```SQL
USE vendas_informatica;

DELETE FROM cliente
WHERE id_cliente = 5;
```

### Instrução 2
```SQL
USE vendas_informatica;

DELETE FROM cliente
WHERE estado = 'SC';
```

### Instrução 3
```SQL
USE vendas_informatica;

DELETE FROM produto
WHERE marca = 'LG';
```

### Instrução 4
```SQL
USE vendas_informatica;

DELETE FROM produto
WHERE id_produto IN (3, 5, 10);
```

### Instrução 5
```SQL
USE vendas_informatica;

DELETE FROM venda
WHERE desconto_percentual = 0;
```

### Instrução 6
```SQL
USE vendas_informatica;

DELETE FROM venda
WHERE status_venda = 'cancelada';
```
