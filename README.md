# siemens-test-5

Colocada a consulta SQL aqui para facilitar a leitura.

SELECT DISTINCT name FROM (  
    SELECT name from public.dogs  
    UNION  
    SELECT name from public.cats  
)  
