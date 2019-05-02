# Tutorial Template

[![GitHubPages](https://github.com/team7033/tutorial-template/blob/master/assets/github%20pages-available-blue.svg)](https://team7033.github.io/tutorial-template/)

__Não esqueça de habilitar o GitHub Pages!__

Aprenda markdown [aqui](https://guides.github.com/features/mastering-markdown/)

## Instruções

Faça o download dos arquivos e crie um novo repositório.

### Estrutura básica

Esse é o código básico do robô.

#### Exemplo de código
```java
package frc.robot;

import edu.wpi.first.wpilibj.TimedRobot;


public class Robot extends TimedRobot {

  @Override
  public void robotInit() {
    // O que estiver aqui dentro será executado apenas uma vez
    // quando o robô for ligado
    // Coloque aqui a inicialização de partes importantes do robô,
    // como por exemplo os motores
  }

  @Override
  public void autonomousInit() {
    // O que estiver aqui também será executado apenas uma vez,
    // mas apenas quando o modo autônomo for ligado
  }

  @Override
  public void autonomousPeriodic() {
    // O que estiver aqui dentro será repetido enquanto o modo 
    // autônomo estiver ligado
  }

  @Override
  public void teleopInit() {
    // O que estiver aqui também será executado apenas uma vez,
    // mas apenas quando o modo teleoperado for ligado
  }

  @Override
  public void teleopPeriodic() {
    // O que estiver aqui dentro será repetido enquanto o modo 
    // autônomo estiver ligado
  }

  @Override
  public void testInit() {
    // O que estiver aqui também será executado apenas uma vez,
    // mas apenas quando o modo teste for ligado
  }

  @Override
  public void testPeriodic() {
    // O que estiver aqui dentro será repetido enquanto o modo 
    // teste estiver ligado
  }
}
```
## Realização

![issoeumaimagem](https://drive.google.com/uc?export=view&id=1jcjX71-6ZGB2BHZH6qmXO15qliTAAUxm)

## Listas

1. Item
2. Item
3. Item

- Item
- Item
- Item

__negrito__

_itálico_
