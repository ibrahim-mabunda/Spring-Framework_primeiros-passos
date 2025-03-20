
### 📖 Explicação do Código

#### 🛠 Estrutura do Projeto
| Elemento                     | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `package dio.springboot.app` | Define o pacote do projeto.                                               |
| `import`                     | Importa bibliotecas necessárias como `Gson` e classes do Spring Framework.|

---

#### 🏃‍♂️ Função Principal
| Elemento                          | Descrição                                                                                       |
|-----------------------------------|-------------------------------------------------------------------------------------------------|
| `public static void main(...)`    | O ponto de entrada da aplicação. Inicia o Spring Boot.                                          |
| `SpringApplication.run(...)`      | Método que inicializa o contexto do Spring Boot.                                               |

---

#### ✨ Definições de Beans
| Bean                           | Descrição                                                                 |
|--------------------------------|---------------------------------------------------------------------------|
| `CommandLineRunner`            | Executa tarefas ao iniciar a aplicação.                                   |
| `run(...)`                     | Contém lógica para converter um JSON em um objeto Java e exibir os dados.|
| `Gson`                         | Bean responsável pela conversão de objetos JSON.                         |

---

#### 🌟 Função do `run(...)`
| Elemento                       | Descrição                                                                 |
|--------------------------------|---------------------------------------------------------------------------|
| `String json`                  | Define um JSON contendo informações de um endereço.                       |
| `ViaCepResponse response`      | Usa o `ConversorJson` para transformar o JSON em um objeto Java.          |
| `System.out.println(...)`      | Exibe os dados convertidos no console.                                    |

---

#### 📦 Anotações do Spring Boot
| Anotação                       | Descrição                                                                 |
|--------------------------------|---------------------------------------------------------------------------|
| `@SpringBootApplication`       | Marca a classe como uma aplicação do Spring Boot.                         |
| `@ComponentScan(...)`          | Especifica o pacote a ser escaneado para encontrar componentes Spring.    |

---

