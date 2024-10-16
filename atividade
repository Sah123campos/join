-- 1
select departamento.nome_depto, funcionario.nome_funcionario from funcionario
inner join departamento on funcionario.sigla_depto = departamento.sigla_depto;

-- 2 

select projeto.nome_projeto, departamento.nome_depto 
from funcionario
inner join projeto on projeto.nome_projeto = projeto.nome_projeto
inner join departamento on departamento.nome_depto = departamento.nome_depto;

-- 3.
SELECT funcionario.nome_funcionario, projeto.nome_projeto
FROM funcionario 
INNER JOIN projeto ON funcionario.codfuncionario = projeto.codfuncionario
WHERE funcionario.sigla_depto = 'VEND';

-- 4
SELECT projeto.nome_projeto, funcionario.nome_funcionario FROM funcionario
LEFT JOIN projeto
ON funcionario.nome_funcionario = projeto.nome_projeto;	

-- 5.
SELECT funcionario.nome_funcionario, departamento.nome_depto
FROM funcionario 
LEFT JOIN departamento ON funcionario.codfuncionario = departamento.sigla_depto;

-- 6.
SELECT projeto.nome_projeto, funcionario.nome_funcionario FROM projeto
LEFT JOIN funcionario ON projeto.codfuncionario = funcionario.codfuncionario;

-- 7. 
SELECT funcionario.nome_funcionario, projeto.nome_projeto FROM funcionario
RIGHT JOIN projeto ON funcionario.codfuncionario = projeto.codfuncionario;

-- 8.
SELECT departamento.nome_depto, funcionario.nome_funcionario FROM departamento
RIGHT JOIN funcionario ON departamento.sigla_depto = funcionario.sigla_depto;

-- 9 
select projeto.nome_projeto, funcionario.nome_funcionario 
FROM funcionario
right join projeto on projeto.nome_projeto = projeto.nome_projeto 


















