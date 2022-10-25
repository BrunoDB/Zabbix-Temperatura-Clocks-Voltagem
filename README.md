# Zabbix-Temperatura-Clocks-Voltagem

Template criado apenas por diversão.
Pode utilizado como desejar.

# Resumo
Foi criado para sistema Windows(AMD e Intel), foi utilizado o LibreHardwareMonitor(V0.9.1) como sensor das informações, mas pode ser utilizado o OpenHardwareMonitor, porém é necessário um pequeno ajuste. 

O template realiza a descoberta de todos os sensores de temperatura, clock e voltagem do dispositivo de forma separada, porém ele se limita a descoberta do LibreHardwareMonitor.
Cria de forma individual cada item descoberto e adiciona o nome do sensor(Não ficou muito bonito), os itens temperatura é criado gráficos para cada item e triggers de temperatura, os itens clock e voltagem apenas coleta as informações e gera gráficos de cada item.

# Pré-requisito.
Executar o LibreHardwareMonitor e deixá-lo rodando em segundo plano.
O software utilizado é Open-source.

Link: [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor)

# Exemplo de Dashboard.
![](/img/Screenshot_12.png)
![](/img/Screenshot_13.png)
![](/img/Screenshot_14.png)
![](/img/Screenshot_15.png)
![](/img/Screenshot_16.png)
![](/img/Screenshot_17.png)
![](/img/Screenshot_18.png)
