# SOLID

S => SRP => Single Responsibility Principle

O	=> OCP => Open / Closed Principle

L	=> LSP => Liskov Substitution Principle

I	=> ISP => Interface Segregation Principle

D	=> DIP => Dependency Inversion Principle

Este projeto tem como intenção demonstrar a violação de cada um dos princípios bem como utilizar os mesmos para a solução e demonstrar como o SOLID pode lhe proporcionar um melhor design de código facilitando a manutenção e o teste.
 		 
## Definições		 
 
Aqui estão os cinco princípios SOLID:

**S - Princípio da Responsabilidade Única (Single Responsibility Principle):**
Este princípio afirma que uma classe deve ter apenas uma razão para mudar, ou seja, deve ter apenas uma responsabilidade. Isso significa que uma classe deve ser focada em fazer uma coisa e fazer isso bem. Se uma classe tem múltiplas responsabilidades, ela se torna mais difícil de manter, entender e testar.

**O - Princípio do Aberto/Fechado (Open/Closed Principle):**
Este princípio afirma que uma classe deve ser aberta para extensão, mas fechada para modificação. Em outras palavras, você deve ser capaz de estender o comportamento de uma classe sem modificar seu código-fonte. Isso é geralmente alcançado através do uso de polimorfismo e interfaces.

**L - Princípio da Substituição de Liskov (Liskov Substitution Principle):**
Este princípio afirma que os objetos de uma classe derivada devem poder ser substituídos por objetos de sua classe base sem interromper o funcionamento do programa. Isso significa que uma subclasse deve ser substituível por sua classe base sem afetar a funcionalidade do programa.

**I - Princípio da Segregação de Interface (Interface Segregation Principle):**
Este princípio afirma que uma classe não deve ser forçada a implementar interfaces que ela não usa. Em vez disso, as interfaces devem ser segregadas em conjuntos menores de métodos relacionados. Isso ajuda a evitar a criação de interfaces monolíticas que contêm métodos não relacionados.

**D - Princípio da Inversão de Dependência (Dependency Inversion Principle):**
Este princípio afirma que as classes de alto nível não devem depender de classes de baixo nível, mas sim de abstrações. Além disso, as abstrações não devem depender de detalhes, mas sim de outras abstrações. Isso significa que o código deve depender de interfaces em vez de implementações concretas, permitindo maior flexibilidade e facilidade de teste.

