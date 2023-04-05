# Aeroportos
Trabalho desenvolvido na disciplina de Linguagem de Programação Orientada a Objetos II - UFPR

Faça um programa que leia o arquivo texto, processo e transforme em objetos contendo os campos: 

1. aeroportoid - Identificador exclusivo do OpenFlights para este aeroporto.
2. Nome - Nome do aeroporto. Pode ou não conter o nome da Cidade.
3. Cidade - Principal cidade servida por aeroporto. Pode ser escrito de forma diferente de Nome.
4. País - País ou território onde o aeroporto está localizado. Consulte Países para fazer referência cruzada aos códigos ISO 3166-1.
5. IATA - Código IATA de 3 letras. Nulo se não atribuído/desconhecido.
6. ICAO - Código ICAO de 4 letras ou Nulo se não atribuído.
7. Latitude - em graus decimais, geralmente com seis dígitos significativos. Negativo é Sul, positivo é Norte.
8. Longitude - em graus decimais, geralmente com seis dígitos significativos. Negativo é Oeste, positivo é Leste.
9. Altitude - em pés.
10. Fuso horário - em Horas deslocadas do UTC. Horas fracionárias são expressas como decimais, por exemplo. A Índia é 5,5.
11. dst - Horário de verão DST. Um de E (Europa), A (EUA/Canadá), S (América do Sul), O (Austrália), Z (Nova Zelândia), N (Nenhum) ou U (Desconhecido). 
13. Fuso horário do banco de dados Tz - Fuso horário no formato "tz" (Olson), por exemplo. "América/Los_Angeles".
14. Tipo - Tipo do aeroporto. Valor "aeroporto" para terminais aéreos, "estação" para estações de trem, "porto" para terminais de balsas e "desconhecido" se não for conhecido. Em Airports.csv, apenas type=airport é incluído.
15. Fonte - Fonte desses dados. "OurAirports" para dados provenientes de OurAirports, "Legacy" para dados antigos não correspondentes a OurAirports (principalmente DAFIF), "User" para contribuições de usuários não verificadas. Em Airports.csv, apenas source=OurAirports está incluído.

Construa uma interface que apresente os principais dados no formato tabela e ao escolher um registro, apresente todos os campos (na mesma tela). As colunas que deverão constar na tabela são: aeroportoid, nome, cidade, país, iata e icao.

Depois, crie uma segunda janela, que permita calcular a distância entre dois aeroportos, onde o usuário informa aeroporto de partida e aeroporto de destino.

Use as informações de latitude e longitude para realizar o calculo
