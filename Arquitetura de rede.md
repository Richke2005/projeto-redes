# 1 Arquitetura de rede 

Para darmos início a elucidação do projeto antes é necessário ententermos o conceito dos seguintes termos, LAN (Local Area Network): Esta rede é utilizada para interconectar dispositivos locais em ambientes geograficamente limitados, embora
atualmente o alcance das redes locais tenha se expandido. Atende às necessidades de uma empresa onde ocorre apenas a comunicação interna entre os hosts e o servidor, com uma forte política de acesso. Nesta rede, a conexão com a internet é realizada
por meio de um único ponto central. As redes LANs são projetadas para operar com alta velocidade de transferência de dados e compartilham diversos recursos internos, como servidores, impressoras e scanners. No entanto, caso haja muitos computadores
ligados ao barramento, um problema pode afetar toda a rede.

MAN (Metropolitan Area Network): Esta rede é projetada para interligar sistemas em regiões metropolitanas, como cidades próximas. Em empresas que atendem a grandes demandas e têm o requisito de realizar comunicação entre as LANs de escritórios
pertencentes a filiais, a MAN é indispensável.

WAN (Wide Area Network): Também chamada de rede de longa distância, ela cobre uma grande área geográfica, normalmente abrangendo o país ou continente. Atende às necessidades de grandes empresas que desejam conectar LANs em escritórios de diversas
partes do mundo. Se a empresa em questão tem a necessidade de trocar informações em nível global, a WAN se torna útil. Como vantagens da rede de longa distância, destacam-se a infraestrutura centralizada e a utilização em grandes áreas geográficas.
No entanto, é uma rede com alto custo de implantação e pode apresentar falhas de segurança, requerendo firewalls e software antivírus para garantir a segurança."


## 1.2 VLANs
As VLANs (virtual local area  network) possibilitam contornar certos problemas que eram observados nas redes físicas LAN, por serem de natureza virtual é possível dimensiona-la, segmentá-la, aumentar as medidas de segurança e diminuir a latência da
rede.
VLANs utilizadas no projeto

![Vlans do projeto](https://th.bing.com/th/id/OIP._5gpjw_bWXHuF4xvlOej6wHaEx?rs=1&pid=ImgDetMain "Vlan")


Foram estruturadas 7 VLANs no projeto para possibilitar a independência de cada setor e assegurar a integridade das redes. Assim se uma for atingida por um malware não afetará as demais.
Uma VLAN, em resumo, é uma espécie de subdivisão de rede que tem a capacidade de agrupar numerosos dispositivos em redes locais físicas separadas. Desse modo, podemos descrever uma LAN (Rede de Área Local) como um conjunto de computadores e dispositivos
que compartilham uma conexão de comunicação ou um link sem fio com um servidor, todos localizados na mesma área geográfica.

Devido às suas características, uma VLAN oferece uma maneira conveniente para os administradores de rede dividirem uma única rede comutada, atendendo assim aos requisitos funcionais e de segurança de seus sistemas, sem a necessidade de instalar novos cabos
ou realizar alterações substanciais na infraestrutura de rede já existente.
