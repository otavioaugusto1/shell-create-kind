# shell-create-kind
Script Shell que utiliza Kind e algumas extensões: Ingress com Nginx e Metallb. 

Problema: normalmente queremos testar nossas aplicações funcionando com o Kubernetes no nosso pc e não ter que subir em alguma cloud pois isso gera custos. Então, normalmente, utilizamos o Kind para isso (Kubernetes in Docker). Porém o Kind, por padrão, vem cru, ou seja, precisamos adicionar Ingress, Metal LB (Loab Balancer), Stack de monitoramento, etc.  
