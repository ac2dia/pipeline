# π pipeline

- CI/CD νμ΅μ μν GitHub Workflow μνμλλ€.
- OpenStack μΈνλΌ νκ²½μμ Kubernetes, Harbor, ArgoCD λ±μ μ΄μ©νλ €κ³  ν©λλ€.

# π κΈ°μ  μ€ν

- openstack / kolla-ansible / xena
- cri-o / kubernetes v1.25
- Harbor
- github workflow / ArgoCD

- golang based web application sample

# π  μν€νμ²

![Architecture](./docs/image/architecture.png)

# π μ£Όμ κΈ°λ₯

- OpenStack κ΅¬μΆ
  - IaaS Infra νκ²½ κ΅¬μΆ
- Private Registry
  - μ»¨νμ΄λ μ΄λ―Έμ§ λ μ§μ€νΈλ¦¬ μ μ₯μ
- Kubernetes κ΅¬μΆ
  - App λ°°ν¬ νκ²½
  - ArgoCD λ°°ν¬

# π  μ€ν νλ©΄

[1] OpenStack μΈνλΌ
![openstack_infra](./docs/image/openstack_infra.png)

[2] kubernetes κ΅¬μ±
![kubernetes](./docs/image/kubernetes.png)

[3] Harbor λ°°ν¬ λ° μ€μ 

- μΆκ° νμ

[4] ArgoCD λ°°ν¬ λ° μ€μ 

- μΆκ° νμ

[5] GitHub Repository μμ± λ° Helm Chart μμ±

- μΆκ° νμ

[6] μ μ²΄ νλ‘μ° νμΈ

- μΆκ° νμ

# π μ§§μ ν

- GitHub Actions μ Workflow λ₯Ό νμ΅ν¨μΌλ‘μ¨ Event, Job, Step μ κ°λ λ° μ¬μ© λ°©λ² μ΅λ
- GitHub Actions νμ΄μ§μμ μ κ³΅νλ workflow μ’λ₯
  - Automation, CI, Deployment, Security, Pages
- ArgoCD νμ΅
- Helm Chart νμ΅

# π TODO

- ArgoCD μ€μ 
  - GitHubμ Helm Chart μ΄μ©ν Repository μμ± ν μ°λ
- GitHub Workflow λ₯Ό ν΅ν΄ νμ€νΈ, μ΄λ―Έμ§ λΉλ
- Helm Chart Repository μ Helm Chart κ°±μ 

- ArgoCD μμ Helm Chart Repository λ³κ²½μ¬ν­μ νμΈν ν μΏ λ²λ€ν°μ€μ ν¬λ¦ μ°¨νΈ λ°°ν¬
  - pod, replicaset, deployment, service(nodePort) λ¦¬μμ€λ₯Ό μ΄μ©νμ¬ λ°°ν¬
  - ingress controller λ₯Ό νμ©ν λ¬΄μ€λ¨ μλ°μ΄νΈ
