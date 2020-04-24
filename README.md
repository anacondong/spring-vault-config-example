# spring-vault-config-example
1)install vault server

2)start server >>> vault server --dev --dev-root-token-id="00000000-0000-0000-0000-000000000000"

3)Insert Key >>> vault kv put secret/spring-vault-config-example anacondong.username=userNameVault anacondong.password=x309742837890823d




# write : 
vault kv put secret/spring-vault-config-example anacondong.username=userNameVault anacondong.password=x309742837890823d

# read : 
vault kv get secret/spring-vault-config-example

# Delete: 
vault kv delete secret/spring-vault-config-example
