# Inventario
tags:
use=onboarding
owner=MateoTorres


VPC laboratory 10.0.0.0/24
subnet laboratory-01 10.0.0.0/28 asignaciondeipspublicas
subnet laboratory-02 10.0.0.16/28 asignaciondeipspublicas
internetgateway laboratory
tabla enrutamiento internet-rtable 0.0.0.0/0 ::/0  internetgateway
target group laboratory
LBA laboratory
asociar el puerto que se expondra

ECS
cluster laboratory
definicion de tarea nginx
servicio

