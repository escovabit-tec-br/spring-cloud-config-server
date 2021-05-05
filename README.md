# spring-cloud-config-server
Servidor de Configurações de Cloud do Spring

## Tutorial - Demo
Demostrando como é a configuração

## Exportando as env
```bash
export config_username=usuariocliente
export config_password=senhadoscliente
export config_git_url=git@github.com:escovabit-tec-br/spring-cloud-config-files.git
export config_private_key=$(cat ~/projetos/escovabit/fake_id_rsa)
```
## Compilando e rodando
```bash
./gradlew build
java -jar build/libs/spring-cloud-config-server-0.0.1-SNAPSHOT.jar
```