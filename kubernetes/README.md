### O painel do Kubernetes Grafana foi atualizado! implantação de kube-state-metrics e instruções de configuração de JOB
### [https://mp.weixin.qq.com/s/R88DraaaS3bpm3PurzpP9g](https://mp.weixin.qq.com/s/R88DraaaS3bpm3PurzpP9g)

---

#### Exibição abrangente de recursos do Kubernetes! Inclui visão geral dos recursos K8S, detalhes de recursos de microsserviço, detalhes de recursos de pod e largura de banda de rede K8S, otimizando a exibição de indicadores importantes.
### Instruções de atualização
##### v20240513
1. Todos os painéis do quadro Kanban foram atualizados para oferecer suporte aos estilos mais recentes, desempenho de exibição otimizado e são compatíveis com a versão Grafana10.X
2. Adicionada barra de status geral do K8S para exibir estatísticas de nós e recursos de microsserviço.
3. Adicionados gráficos de curva de uso de PVC, CPU e uso de memória de cada namespace.
4. Otimizou os campos de exibição e os efeitos visuais das tabelas de detalhes de recursos de microsserviço e pod.
5. Otimizado o gráfico de curva de uso de CPU e memória de pod e microsserviço para exibir diretamente a linha vermelha do valor limite do recurso.
6. Corrigido o bug que causava a exibição imprecisa de dados de recursos do pod em um curto período de tempo devido à reinicialização do pod.
7. Ajustou os efeitos de exibição e as descrições de vários gráficos e gráficos de curvas e otimizou alguns dados do indicador para serem mais precisos.
8. Adicionadas imagens domésticas de várias versões do kube-state-metrics Referência [[aqui]](https://github.com/starsliao/Prometheus/tree/master/kubernetes)
9. Adicionadas instruções de configuração de JOB para Prometheus no K8S.

---

### captura de tela
#### Visão geral geral dos recursos
![](https://grafana.com/api/dashboards/13105/images/16207/image)
![](https://grafana.com/api/dashboards/13105/images/16208/image)
#### Detalhes do recurso do pod
![](https://grafana.com/api/dashboards/13105/images/16209/image)
#### Detalhes do recurso de microsserviço
![](https://grafana.com/api/dashboards/13105/images/16210/image)

### Aprecie e siga a conta pública [**Cloud Native DevOps**] e junte-se ao grupo de comunicação (observe: K8S) para obter mais...

**Se você não consegue ver a imagem, clique neste link: [https://starsl.cn/static/img/thanks.png](https://starsl.cn/static/img/thanks.png)**
![](https://starsl.cn/static/img/thanks.png)

---

### Baixar Kanban
ID da placa Grafana: 13105
- Endereço do painel Grafana: [https://grafana.com/grafana/dashboards/13105](https://grafana.com/grafana/dashboards/13105)
- Armazém do projeto: [https://github.com/starsliao/Prometheus/tree/master/kubernetes](https://github.com/starsliao/Prometheus/tree/master/kubernetes)