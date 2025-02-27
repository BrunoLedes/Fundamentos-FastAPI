Execultar no terminal com o comando: uvicorn api:app --reload

uvicorn api:app  = caminho configurado para startar o servidor ASGI
uvicorn: Chama o servidor Uvicorn.

api: Refere-se ao nome do arquivo Python (api.py) onde a aplicação está definida.

app: Refere-se ao nome da instância da aplicação ASGI dentro do arquivo (api.py).


-- reload = no Uvicorn faz com que o servidor seja recarregado automaticamente 
sempre que um arquivo do projeto for modificado.
