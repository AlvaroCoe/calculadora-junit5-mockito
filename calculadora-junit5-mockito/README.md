# calculadora-junit5-mockito

Projeto Java 17 + Maven + JUnit 5 + Mockito 5 (Calculadora).

## Como executar
```
mvn clean test       # 10 testes (CT01 a CT10)
mvn clean package    # gera target/calculadora-junit5-mockito-1.0-SNAPSHOT.jar
```

## Estrutura
- `Calculadora`: soma, sub, mult, divisao
- `HistoricoOperacoes`: dependência externa (mockada nos testes)
- `CalculadoraService`: usa a Calculadora e registra no histórico
- `CalculadoraTest`: CT01–CT05 (JUnit 5)
- `CalculadoraServiceTest`: CT06–CT10 (Mockito)
