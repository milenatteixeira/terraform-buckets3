Terraform - Bucket S3

*Obs.: É indicado rodar os comandos dentro de um contâiner do Docker.*

- Para iniciar o projeto, siga o passo a passo abaixo:
  - Modifique as variáveis nos arquivos _main.tf_ e _variable.tf_
  - Dentro do Docker, utilize:
    - terraform init
    - terraform plan -out plan
    - terraform apply -auto-approve plan
