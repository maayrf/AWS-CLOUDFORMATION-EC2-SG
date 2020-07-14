# AWS-CLOUDFORMATION-EC2-SG
AWS Cloudformation com EC2 e acessos ao Security Group via SSH, HTTP e HTTPS. Sua rede utiliza a VPC Default da sua AWS!

Faça download deste template "ec2-sg.yaml";
Entre na console AWS;
CloudFormation; Stacks;
Create stack;
Template is ready;
Upload a template file;
Selecione o template que foi feito download;
E configure com o nome que deseja para sua Stack;
O acesso HTTP, HTTPS e SSH estão com permissões padrões para 0.0.0.0/0;
O tipo da instância esta por padrão a t2.miro, mas se quiser pode alterar no "InstanceType" do .yaml;
No código yaml você consegue liberar o Security Group para mais outras porta (acrescente um "XLocation" e um "IpProtocol" no "InstanceSecurityGroup").
