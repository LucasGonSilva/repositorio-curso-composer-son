# Meu pacote

Exemplo de um curso

## Exemplo de utilização

```
use Lucassilva\CursoSON\Hello;

$log = new Monolog\Logger('name');
$log->pushHandler(new Monolog\Handler\StreamHandler('app.log', Monolog\Logger::WARNING));

$log->warning((new Hello)->say('Lucas'));

```