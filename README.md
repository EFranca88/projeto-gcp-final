# Desafio Pipeline CICD Cloud Build + Terraform.

Neste projeto, será implantado uma infraestrutura baseada em Linux a partir do Cloud Build e Terraform.

* Bucket que hospedará o estado do terraform.

![Alt text](images/bucket-gcp.png?raw=true "Bucket para o estado terraform")

* Gatilho criado no Cloud Build, que será disparado sempre que um novo commit for criado no repositório.

![Alt text](images/gatilho-cloudbuild.png?raw=true "Gatilho criado no Cloud Build")

* Evidencia do deploy de maquina Linux atraves do Cloud Build com Terraform.

![Alt text](images/projeto-funcional.png?raw=true "Cloud Build com Terraform executado com sucesso")