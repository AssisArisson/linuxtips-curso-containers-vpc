



provider.aws (5.62.0)




resource.aws_eip.vpc_eip_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eip)
resource.aws_eip.vpc_eip_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eip)
resource.aws_eip.vpc_eip_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eip)
resource.aws_internet_gateway.gw (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/internet_gateway)    
resource.aws_nat_gateway.nat_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/nat_gateway)
resource.aws_nat_gateway.nat_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/nat_gateway)
resource.aws_nat_gateway.nat_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/nat_gateway)
resource.aws_route.private_access_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route)
resource.aws_route.private_access_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route)
resource.aws_route.private_access_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route)
resource.aws_route.public_acces (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route)
resource.aws_route_table.private_internet_access_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table)
resource.aws_route_table.private_internet_access_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table)
resource.aws_route_table.private_internet_access_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table)
resource.aws_route_table.public_internet_access (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table)
resource.aws_route_table_association.private_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)
resource.aws_route_table_association.private_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)
resource.aws_route_table_association.private_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)
resource.aws_route_table_association.public_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)
resource.aws_route_table_association.public_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)
resource.aws_route_table_association.public_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)
resource.aws_ssm_parameter.databases_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)
resource.aws_ssm_parameter.databases_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)
resource.aws_ssm_parameter.databases_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)
resource.aws_ssm_parameter.private_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)  
resource.aws_ssm_parameter.private_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)  
resource.aws_ssm_parameter.private_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)  
resource.aws_ssm_parameter.public_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)   
resource.aws_ssm_parameter.public_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)   
resource.aws_ssm_parameter.public_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)   
resource.aws_ssm_parameter.vpc (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter)
resource.aws_subnet.databases_subnet_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)       
resource.aws_subnet.databases_subnet_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)       
resource.aws_subnet.databases_subnet_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)       
resource.aws_subnet.private_subnet_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)
resource.aws_subnet.private_subnet_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)
resource.aws_subnet.private_subnet_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)
resource.aws_subnet.public_subnet_1a (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)
resource.aws_subnet.public_subnet_1b (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)
resource.aws_subnet.public_subnet_1c (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)
resource.aws_vpc.main (resource) (https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc)


input.project_name (required)
n/a

input.region (required)
n/a


output.ssm_subnet_databases_1a
ID da subnet de bancos de dados na zona de disponibilidade 1a. Este ID é recuperado do AWS Systems Manager Parameter Store e usado para o provisionamento de instâncias de banco de dados nesta zona específica.

output.ssm_subnet_databases_1b
ID da subnet de bancos de dados na zona de disponibilidade 1b. Obtido do AWS Systems Manager Parameter Store, é essencial para a alocação de instâncias de banco de dados que precisam ser isoladas nesta zona.

output.ssm_subnet_databases_1c
ID da subnet de bancos de dados na zona de disponibilidade 1c, proveniente do AWS Systems Manager Parameter Store. Utilizado no provisionamento de instâncias de banco de dados que requerem isolamento nesta zona.

output.ssm_subnet_private_1a
ID da subnet privada na zona de disponibilidade 1a. Valor armazenado no AWS Systems Manager Parameter Store, utilizado para provisionar recursos em uma subnet privada específica.

output.ssm_subnet_private_1b
ID da subnet privada na zona de disponibilidade 1b. Armazenado no AWS Systems Manager Parameter Store, usado para alocação de recursos que requerem isolamento dentro desta zona de disponibilidade.

output.ssm_subnet_private_1c
ID da subnet privada na zona de disponibilidade 1c. Guardado no AWS Systems Manager Parameter Store, é crucial para a criação de recursos que precisam ser isolados nesta zona específica.

output.ssm_subnet_public_1a
ID da subnet pública na zona de disponibilidade 1a. Este ID, proveniente do AWS Systems Manager Parameter Store, é utilizado para provisionar recursos acessíveis publicamente nesta zona.

output.ssm_subnet_public_1b
ID da subnet pública na zona de disponibilidade 1b. Disponível via AWS Systems Manager Parameter Store, permite a implementação de recursos com acesso público nesta zona específica.

output.ssm_subnet_public_1c
ID da subnet pública na zona de disponibilidade 1c, armazenado no AWS Systems Manager Parameter Store. Usado para configurar recursos que necessitam de acesso público nesta zona.

output.ssm_vpc_id
ID do VPC armazenado no AWS Systems Manager Parameter Store. Este ID é usado para identificar o VPC onde os recursos serão provisionados.   