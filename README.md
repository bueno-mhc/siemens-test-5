# siemens-test-5

SELECT DISTINCT name FROM (  
    SELECT name from public.dogs  
    UNION  
    SELECT name from public.cats  
)  
