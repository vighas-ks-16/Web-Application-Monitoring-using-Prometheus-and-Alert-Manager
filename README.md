# Web-Application-Monitoring-using-Prometheus-and-Alert-Manager
Real-Time Monitoring of Web Application with E-Mail Alerts


## Using Prometheus for Monitoring

- Prometheus is an open-source monitoring and alerting system that helps you collect and store metrics about your software systems and infrastructure, and analyze that data to gain insights into their health and performance.
- It provides a powerful query language, a flexible data model, and a range of integrations with other tools and systems.
- With Prometheus, you can easily monitor metrics such as CPU usage, memory usage, network traffic, and application-specific metrics, and use that data to troubleshoot issues, optimize performance, and create alerts to notify you when things go wrong.

<br></br>

## Reasons for using Prometheus over other Monitoring Tools :

Prometheus is a popular choice for Kubernetes monitoring for several reasons:

- Open-source: Prometheus is an open-source project that is free to use and has a large community of contributors. This means that you can benefit from ongoing development, bug fixes, and feature enhancements without paying for a commercial monitoring solution.

- Native Kubernetes support: Prometheus is designed to work seamlessly with Kubernetes, making it easy to deploy and integrate with your Kubernetes environment. It provides pre-configured Kubernetes dashboards and supports auto-discovery of Kubernetes services and pods.

- Powerful query language: Prometheus provides a powerful query language that allows you to easily retrieve and analyze metrics data. This allows you to create custom dashboards and alerts, and to troubleshoot issues more easily.

- Scalability: Prometheus is designed to be highly scalable, allowing you to monitor large and complex Kubernetes environments with ease. It supports multi-node architectures and can handle large volumes of data without significant performance degradation.

- Integrations: Prometheus integrates with a wide range of other tools and systems, including Grafana for visualization, Alertmanager for alerting, and Kubernetes API server for metadata discovery.

<br></br>


## PROMETHEUS ARCHITECTURE :

![image](https://github.com/user-attachments/assets/47201765-cd70-4fe2-8afd-3271ab019811)


## PROJECT WORKFLOW :

![WhatsApp Image 2024-07-17 at 22 43 25_4a3c16b6](https://github.com/user-attachments/assets/4e300fea-2814-47c4-a34c-ec9bb3010555)


## PREREQUISITES :

- Two EC2 Instances (The Website is allowed to run in an EC2 Instance and the Monitoring tools like Prometheus, Alert Manager and BlackBox exporter are allowed to run in another EC2 Instance)
- Prometheus
- BlackBox Exporter
- Alert Manager
- Node Exporter


## PROJECT IMPLEMENTATION :

![WhatsApp Image 2024-07-17 at 23 05 33_3bdbe72a](https://github.com/user-attachments/assets/8190061c-ca10-4c4f-92eb-bf22c499e891)


## Prometheus Installation :

![WhatsApp Image 2024-07-17 at 23 10 25_95c205b5](https://github.com/user-attachments/assets/d70486b9-9812-4a6f-89ab-b68242d81bc0)

![WhatsApp Image 2024-07-17 at 23 10 26_cf3ac8f0](https://github.com/user-attachments/assets/7267ebe6-aceb-4090-835b-a2312d946f1e)

Extraction of Prometheus Archive :

![WhatsApp Image 2024-07-17 at 23 10 26_afdea4b5](https://github.com/user-attachments/assets/4b49437f-22c8-48a4-80c6-8f3a22f24efd)

![WhatsApp Image 2024-07-17 at 23 10 27_bf5ed208](https://github.com/user-attachments/assets/8b269d38-b837-4d4e-be6a-3f1fe27a6063)

## BlackBox Exporter Installation :

![WhatsApp Image 2024-07-17 at 23 10 27_8c8a23e8](https://github.com/user-attachments/assets/8fe71088-8837-4abc-a5a8-bf624751bc3a)

![WhatsApp Image 2024-07-17 at 23 10 27_9e47612d](https://github.com/user-attachments/assets/511551f4-8569-4d5a-92d9-1d87cb8be0a0)

Extraction of BlackBox Exporter Archive :

![WhatsApp Image 2024-07-17 at 23 10 28_f4982b67](https://github.com/user-attachments/assets/9cb5212c-72cf-4062-b6b6-f0d02ef6a92d)

![WhatsApp Image 2024-07-17 at 23 10 28_d80583eb](https://github.com/user-attachments/assets/3bf381b4-99d8-46de-add9-037acc178be5)

## AlertManager Installation :

![WhatsApp Image 2024-07-17 at 23 10 29_73055d02](https://github.com/user-attachments/assets/9207f166-6505-413e-b43c-1008e96fa25f)

Extraction of AlertManager Archive :

![WhatsApp Image 2024-07-17 at 23 10 29_8abeecc6](https://github.com/user-attachments/assets/ab5c5d89-641c-4d4c-a771-5256ae15be31)

## Cloning the Git Repo of the Sample Website in another EC2 Instance :

![WhatsApp Image 2024-07-17 at 23 26 33_85d105ab](https://github.com/user-attachments/assets/987f6671-566c-4c12-b777-0a380da2cbf9)

## NodeExporter Installation :

![WhatsApp Image 2024-07-17 at 23 27 23_1736539f](https://github.com/user-attachments/assets/1e93e3f1-8a4e-4396-b0d4-69fee55a8a4d)

Extraction of NodeExporter Archive :

![WhatsApp Image 2024-07-17 at 23 27 23_7b2d7ea1](https://github.com/user-attachments/assets/1d7b0296-1de3-42fd-9aca-a698d73bb3f3)

## The Sample Website and the NodeExporter in the same EC2 Instance :

![WhatsApp Image 2024-07-17 at 23 27 24_9b82f5b4](https://github.com/user-attachments/assets/183a92df-b78d-4563-ad43-336c33d50f7b)

![WhatsApp Image 2024-07-17 at 23 37 19_9283adac](https://github.com/user-attachments/assets/c2d7643b-8fcd-4002-8dcb-ca03763a656c)

![WhatsApp Image 2024-07-17 at 23 37 19_fa95e48a](https://github.com/user-attachments/assets/7fe3d7ae-9876-48d4-831d-5fe4c13985ab)

![WhatsApp Image 2024-07-17 at 23 37 20_db0ea45d](https://github.com/user-attachments/assets/5c0143f9-ba12-439b-8813-5aebe788f42c)

![WhatsApp Image 2024-07-17 at 23 37 20_485386d1](https://github.com/user-attachments/assets/8fb7af66-5954-41a9-b09c-dfa8e98f7bab)

## Java, Maven and SpringBoot Installation :

![WhatsApp Image 2024-07-17 at 23 43 44_f6c1651e](https://github.com/user-attachments/assets/33c343a6-86bc-432f-96d5-e413412019e0)

![WhatsApp Image 2024-07-17 at 23 43 44_08d436fb](https://github.com/user-attachments/assets/be54e25d-4cd2-4067-85c0-707ca1a62da2)

![WhatsApp Image 2024-07-17 at 23 43 44_b7637686](https://github.com/user-attachments/assets/1d7c07e1-a707-4bd8-80f0-6cec125e75c5)

![WhatsApp Image 2024-07-17 at 23 43 45_88fe73c3](https://github.com/user-attachments/assets/58cd15b8-4fbc-4a4e-a13b-33e2c79fd453)

![WhatsApp Image 2024-07-17 at 23 43 45_ea880fc1](https://github.com/user-attachments/assets/7abbc35a-7e03-44a9-a5d7-bf5b97f43e67)

![WhatsApp Image 2024-07-17 at 23 43 45_a3894155](https://github.com/user-attachments/assets/bff406c8-c6fe-46f1-a0ce-87b620580a4a)

![WhatsApp Image 2024-07-17 at 23 43 46_9ecb9df9](https://github.com/user-attachments/assets/79abc52e-601c-4353-bcd9-0d6e19ebb00f)

![WhatsApp Image 2024-07-17 at 23 43 46_34ce040a](https://github.com/user-attachments/assets/7cf71351-f835-40a7-a538-596b3757b657)

## Sample Website :

![WhatsApp Image 2024-07-17 at 23 43 47_bdd9ac7d](https://github.com/user-attachments/assets/96ddf46a-4e65-44d2-8b48-59a6fea7eecc)

## Running Prometheus in the Background :

![WhatsApp Image 2024-07-17 at 23 50 29_233cf161](https://github.com/user-attachments/assets/f5169851-94e3-4ef7-9a5f-d3726d919983)

![WhatsApp Image 2024-07-17 at 23 50 29_06da9cf2](https://github.com/user-attachments/assets/a4800605-268b-4582-9f1e-12c4f539bd8f)

![WhatsApp Image 2024-07-17 at 23 50 30_489f8001](https://github.com/user-attachments/assets/ec05bbcc-dbda-4b10-a6a7-939246fb49ea)

![WhatsApp Image 2024-07-17 at 23 50 30_135c3b15](https://github.com/user-attachments/assets/6bcdee6e-64d5-4d71-baae-f8658340bbf4)

![WhatsApp Image 2024-07-17 at 23 50 31_f7f0714d](https://github.com/user-attachments/assets/13a8e9c2-b949-43f9-a8d3-c4f0caf492fd)

## alertmanager.yml :

![WhatsApp Image 2024-07-17 at 23 55 15_356b7a51](https://github.com/user-attachments/assets/fd5aef7e-b479-4cf9-829c-9105a5f4064a)

![WhatsApp Image 2024-07-17 at 23 55 16_1cea0ccf](https://github.com/user-attachments/assets/de05a628-f8c9-43c9-b682-487fd3b5e0f0)

## alertrules.yml :

![WhatsApp Image 2024-07-17 at 23 55 16_4c3d8939](https://github.com/user-attachments/assets/82bca71b-40b2-4a0c-a130-4cdcfaf88cf9)

![WhatsApp Image 2024-07-17 at 23 55 17_6733a84d](https://github.com/user-attachments/assets/0ae18deb-ab7f-43a1-9bc8-9e8a9dd51225)

## prometheus.yml :

![WhatsApp Image 2024-07-17 at 23 57 38_1eb3d43a](https://github.com/user-attachments/assets/b121a9c4-c40f-496c-8f65-02c0ec4634f2)

## Running AlertManager in the Background :

![WhatsApp Image 2024-07-18 at 00 00 01_50686c1b](https://github.com/user-attachments/assets/7b254291-bd7c-42e4-a9a3-601281e003b0)

![WhatsApp Image 2024-07-18 at 00 00 01_3199a6ab](https://github.com/user-attachments/assets/a651b04c-0db2-4c31-bcb3-e6c7dcc4c0c7)

![WhatsApp Image 2024-07-18 at 00 00 02_4408fa5a](https://github.com/user-attachments/assets/6c559d86-3667-4eb6-b48f-01b51d66ea43)

## Killing the Prometheus by using the process id :

![WhatsApp Image 2024-07-18 at 00 01 37_8e1ab69e](https://github.com/user-attachments/assets/207ed20b-9c95-4ee1-ab6d-ac989da7a69c)

## Restarting the Prometheus again in the Background :

![WhatsApp Image 2024-07-18 at 00 01 38_77f9470f](https://github.com/user-attachments/assets/e598cd27-0453-4527-8d98-616a576031ca)

![WhatsApp Image 2024-07-18 at 00 01 38_dfa0b4cb](https://github.com/user-attachments/assets/a59750b0-f5d5-4ec5-ab98-d232c6205e1c)

## prometheus.yml :

![WhatsApp Image 2024-07-18 at 00 12 08_f2007453](https://github.com/user-attachments/assets/20d90b1b-6ebb-4e9c-b577-2370eb76432f)

![WhatsApp Image 2024-07-18 at 00 12 08_3abe937c](https://github.com/user-attachments/assets/5d3ff3b8-776e-486a-8831-4def06efdc22)

![WhatsApp Image 2024-07-18 at 00 12 09_9f08c7a6](https://github.com/user-attachments/assets/b0082ee5-ad96-436a-a084-81ade30fe53f)

![WhatsApp Image 2024-07-18 at 00 12 09_48d0ec69](https://github.com/user-attachments/assets/1e1d16b6-cd5a-4a1d-9910-b54563168476)

![WhatsApp Image 2024-07-18 at 00 12 09_d5367650](https://github.com/user-attachments/assets/84b112ba-510c-41e1-9ed0-63e5dd0e6ea8)

![WhatsApp Image 2024-07-18 at 00 12 10_5810e32b](https://github.com/user-attachments/assets/201bc6a5-dc5b-4f17-bea5-1bcf8c39b031)

![WhatsApp Image 2024-07-18 at 00 12 10_92fa2c76](https://github.com/user-attachments/assets/f495047b-d77b-42b8-8f24-3b427ea19032)

![WhatsApp Image 2024-07-18 at 00 12 11_85df0d3c](https://github.com/user-attachments/assets/4d3f22de-1031-4a94-9974-2128fbccca6c)

## BlackBox Exporter Up :

![WhatsApp Image 2024-07-18 at 00 12 11_7a660cc7](https://github.com/user-attachments/assets/a85e5d78-35eb-4766-b0fd-b65c2deddfb5)

![WhatsApp Image 2024-07-18 at 00 12 11_053891d8](https://github.com/user-attachments/assets/787e81c4-704f-4b7f-8d62-05926483546f)

## alertmanager.yml :

![WhatsApp Image 2024-07-18 at 00 12 12_5bf609a5](https://github.com/user-attachments/assets/bea2a6db-28f6-4b49-828a-9e714bbb674a)

![WhatsApp Image 2024-07-18 at 00 12 12_e76e4c7b](https://github.com/user-attachments/assets/6e068ec1-2c5c-47e8-a823-14db6e23011b)

![WhatsApp Image 2024-07-18 at 00 12 12_522b1e78](https://github.com/user-attachments/assets/580bc33f-3880-4592-bc99-914603d6b82a)

![WhatsApp Image 2024-07-18 at 00 12 13_6672d66c](https://github.com/user-attachments/assets/fa56e040-8fda-4ef0-bfa4-2d0a28815ca6)

![WhatsApp Image 2024-07-18 at 00 12 13_b3260314](https://github.com/user-attachments/assets/0c229f6e-5699-4798-8384-9c48b05aedef)

## Prometheus with the Alert Rules configured :

![WhatsApp Image 2024-07-18 at 00 12 13_f7cc3adc](https://github.com/user-attachments/assets/2f275e3b-7d51-4355-b125-92d0bf78f222)

## Making the Website Down :

![WhatsApp Image 2024-07-18 at 00 12 14_3e2cabd1](https://github.com/user-attachments/assets/9ba5fc3b-e55b-46e5-a208-f64647563d33)

![WhatsApp Image 2024-07-18 at 00 12 14_628348bd](https://github.com/user-attachments/assets/3e975a3a-9e54-436e-9e92-ba6d064fb8cb)

## Alerts in the Prometheus Dashboard :

![WhatsApp Image 2024-07-18 at 00 12 16_a82b77c1](https://github.com/user-attachments/assets/f034425d-493e-4bfb-8912-fff2303fb389)

![WhatsApp Image 2024-07-18 at 00 12 17_d257d8c2](https://github.com/user-attachments/assets/6269c7c8-31cc-4f8e-9c6f-9240377230fb)

![WhatsApp Image 2024-07-18 at 00 12 17_38467759](https://github.com/user-attachments/assets/e316ac54-31e1-456e-ae5b-8016156b8718)

![WhatsApp Image 2024-07-18 at 00 12 18_818f9e5f](https://github.com/user-attachments/assets/4585f07a-32fc-4426-a5a2-02cf121a53ad)


## E-Mail Notification for Website Down :

![WhatsApp Image 2024-07-18 at 00 12 16_6a2a5d4c](https://github.com/user-attachments/assets/e62a3418-72a5-45f2-916a-a19ead68057c)

## E-Mail Notification for Instance Down :

![WhatsApp Image 2024-07-18 at 00 12 18_8513f049](https://github.com/user-attachments/assets/840c7b53-fdb9-4a58-8a8e-093cd7b0d38d)

## E-Mail Notification for Service Unavailable :

![WhatsApp Image 2024-07-18 at 00 12 19_429e5eae](https://github.com/user-attachments/assets/5bda3069-8bc6-4b23-a285-a7bc0b043771)












































































