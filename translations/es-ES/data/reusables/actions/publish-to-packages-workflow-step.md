Ejecuta el comando `mvn --batch-mode deploy` para publicar a {% data variables.product.prodname_registry %}. La variable de ambiente `GITHUB_TOKEN` se configurará con el contenido del secreto `GITHUB_TOKEN`. The `permissions` key specifies the access granted to the `GITHUB_TOKEN`.