# Paleta de Cores - Inserts SQL

Este README contém os comandos SQL necessários para inserir uma paleta de cores em um banco de dados.

## Como utilizar

1. Certifique-se de que possui um banco de dados criado e configurado corretamente.
2. Execute os comandos SQL a seguir para inserir a paleta de cores no banco de dados.

## Criação da tabela

```sql
create table cor (
id serial not null,
descricao varchar(50) not null,
hexadecimal varchar(7) not null,
data_cadastro timestamp not null,
constraint pk_cor primary key(id)
);
```

## Comandos SQL para inserção da paleta de cores

```sql
-- Inserção da paleta de cores
insert into cor(descricao, hexadecimal, data_cadastro) values ('Água','#00FFFF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul turquesa','#00CCEE', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul turquesa brilhante','#00DDFF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul brasilis','#00BDCE', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul brasilis brilhante','#09ACDB', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul Tóquio','#1981CD', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Água-marinha','#7FFFD4', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Água-marinha média','#66CDAA', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul celeste','#00A4CD', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Alizarina','#E32636', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo','#FFFF00', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo brasilis','#ECDB00', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo creme','#ECD690', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo claro','#FFFFE0', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo escuro','#F2B73F', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo esverdeado','#ADFF2F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo ouro claro','#FAFAD2', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amarelo queimado','#EEAD2D', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Âmbar','#FFBF00', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ameixa','#DDA0DD', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ametista','#9966CC', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Amêndoa','#FFEBCD', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Aspargo','#7BA05B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul','#0000FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul alice','#F0F8FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul ardósia','#6A5ACD', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul ardósia claro','#8470FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul ardósia escuro','#483D8B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul ardósia médio','#7B68EE', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul areado','#B8CAD4', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul aço','#4682B4', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul aço claro','#B0C4DE', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul cadete','#5F9EA0', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul camarada','#054F77', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul celeste','#F0FFFF', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul celeste brilhante','#007FFF', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul claro','#ADD8E6', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul cobalto','#0047AB', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul céu','#87CEEB', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul céu claro','#87CEFA', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul céu profundo','#00BFFF', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul escuro','#00008B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul flor de milho','#6495ED', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul força aérea','#5D8AA8', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul furtivo','#1E90FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul manteiga','#a6aa3e', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul marinho','#120A8F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul meia-noite','#191970', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul médio','#0000CD', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul petróleo','#084D6E', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul pólvora','#B0E0E6', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul taparuere','#248EFF', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul real','#0000DD', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Azul violeta','#8A2BE2', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Açafrão','#F4C430', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Bege','#F5F5DC', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Bordô','#800000', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Borgonha','#900020', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Branco','#FFFFFF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Branco antigo','#FAEBD7', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Branco fantasma','#F8F8FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Branco floral','#FFFAF0', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Branco fumaça','#F5F5F5', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Branco navajo','#FFDEAD', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Brasil','#A7F432', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Bronze','#CD7F32', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Caramelo','#8B5742', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Caqui','#F0E68C', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cardo','#D8BFD8', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Carmesim','#DC143C', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Carmim','#712F26', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Carmim clássico','#992244', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Carmim carnáceo','#960018', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Castanho avermelhado','#8B0000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Castanho claro','#D2B48C', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cenoura','#ED9121', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cereja','#DE3163', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cereja Hollywood','#F400A1', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Chocolate','#D2691E', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ciano','#00FFFF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ciano claro','#E0FFFF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ciano escuro','#008B8B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza','#808080', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza ardósia','#708090', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza ardósia claro','#778899', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza ardósia escuro','#2F4F4F', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza claro','#D3D3D3', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza escuro','#A9A9A9', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza fosco','#696969', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cinza médio','#DCDCDC', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Cobre','#B87333', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Concha','#FFF5EE', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Coral','#FF7F50', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Coral claro','#F08080', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Couro','#F0DC82', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Creme','#FFFDD0', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Creme de marisco','#FFE4C4', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Creme de menta','#F5FFFA', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Caqui escuro','#BDB76B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Dainise','#778899', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Dourado','#DAA520', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Dourado escuro','#B8860B', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Dourado pálido','#EEE8AA', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ébano','#555D50', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Eminência','#6C3082', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Escarlate','#FF2400', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Esmeralda','#50C878', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Eucalipto','#44D7A8', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Fandango','#B53389', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Feldspato','#FDD5B1', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ferrugem','#B7410E', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Flerte','#A2006D', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Fuligem','#3D2B1F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Fúchsia','#FF00FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Grená','#831D1C', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Gainsboro','#DCDCDC', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Glitter','#E6E8FA', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Goiaba','#Be5b59', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Herbal','#2E8B57', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Heliotrópio','#DF73FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Índigo','#4B0082', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Independência','#4C516D', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Iris','#5A4FCF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Jade','#00A86B', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Jambo','#FF4500', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Jasmine','#F8DE7E', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Kiwi','#8EE53F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Kobi','#E79FC4', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Kobicha','#6B4423', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Laranja','#FFA500', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Laranja escuro','#FF8C00', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Laranja claro','#FFB84D', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Lavanda','#E6E6FA', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Lavanda avermelhada','#FFF0F5', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Lilás','#C8A2C8', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Lima','#00FF00', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Lemon','#FDE910', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Linho','#FAF0E6', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Madeira','#DEB887', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Magenta','#FF00FF', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Magenta escuro','#8B008B', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Malva','#E0B0FF', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Mamão batido','#FFEFD5', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Maná','#F0FFF0', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Marfim','#FFFFF0', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Marrom','#964b00', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Marrom amarelado','#F4A460', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Marrom claro','#A52A2A', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Marrom rosado','#BC8F8F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Marrom sela','#8B4513', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Milho','#FBEC5D', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Milho Claro','#FFF8DC', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Mocassim','#FFE4B5', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Mostarda','#FFDB58', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Naval','#000080', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Neve','#FFFAFA', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Nyanza','#E9FFDB', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ocre','#CC7722', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Oliva','#808000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Oliva escura','#556B2F', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Oliva parda','#6B8E23', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Orquídea','#DA70D6', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Orquídea escura','#9932CC', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Orquídea média','#BA55D3', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ouro','#FFD700', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Pardo','#CD853F', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Pardo escuro','#CC6600', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Prata','#C0C0C0', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Preto','#000000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Pêssego','#FFDAB9', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Púrpura','#800080', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Púrpura média','#9370DB', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Quantum','#111111', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Quartz','#51484F', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Renda antiga','#FDF5E6', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa','#FFCBDB', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa brilhante','#FF007F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa Choque','#FC0FC0', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa amoroso','#CD69CD', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa claro','#FFB6C1', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa danação','#DA69A1', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa embaçado','#FFE4E1', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa forte','#FF69B4', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rosa profundo','#FF1493', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Roxo','#993399', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Roxo brasilis','#8A008A', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Rútilo','#6D351A', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Salmão','#FA7F72', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Salmão claro','#FFA07A', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Salmão escuro','#E9967A', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Siena','#FF8247', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Sépia','#705714', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Tangerina','#F28500', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Terracota','#E2725B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Tijolo refratário','#B22222', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Tomate','#FF6347', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Trigo','#F5DEB3', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Triássico','#FF2401', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Turquesa','#40E0D0', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Turquesa escura','#00CED1', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Turquesa média','#48D1CC', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Turquesa pálida','#AFEEEE', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Ube','#8878C3', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Urucum','#EC2300', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde','#008000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde espectro','#00FF00', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde amarelado','#9ACD32', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde claro','#90EE90', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde escuro','#006400', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde floresta','#228B22', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde fluorescente','#CCFF33', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde lima','#32CD32', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde grama','#7CFC00', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde mar claro','#20B2AA', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde mar escuro','#8FBC8F', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde mar médio','#3CB371', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde militar','#78866B', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde-oliva','#6B8E23', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde Paris','#7FFF00', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde primavera','#00FF7F', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde primavera médio','#00FA9A', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde pálido','#98FB98', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Verde-azulado','#008080', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho','#FF0000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho enegrecido','#550000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho escuro','#8B0000', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho indiano','#CD5C5C', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho violeta','#D02090', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho violeta médio','#C71585', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Vermelho violeta pálido','#DB7093', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Violeta','#EE82EE', current_date);
insert into cor(descricao, hexadecimal, data_cadastro) values ('Violeta escuro','#9400D3', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Violeta claro','#F8CBF8', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Xanadu','#738678', current_date);	
insert into cor(descricao, hexadecimal, data_cadastro) values ('Zaffre','#0014A8', current_date);	
-- Adicione mais cores conforme necessário
```

## Material de apoio
[Referência](https://pt.wikipedia.org/wiki/Lista_de_cores)

