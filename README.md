<p align="center">
<img src="https://img.shields.io/badge/VERSÃO-1.0.0-green">
<img src="https://img.shields.io/badge/Licença-GNU 3.0-success">
<img src="https://img.shields.io/badge/PHP-Adianti-blue">
</p>

## Instalação

> 1 - Baixe o arquivo e coloque na pasta: "app/resources/css/"<br>
> 2 - Na classe __construct do seu KANBAN inclua a linha:



``` parent::include_css("app/resources/css/kanban.css"); ```

<p>
Sua classe irá ficar assim:
</p>

```
class KanbanDatabaseView extends TPage
{
    private $form;
    private static $database = "sistema";
    
    public function __construct()
    {
        parent::__construct();
        parent::include_css("app/resources/css/kanban.css");
```
