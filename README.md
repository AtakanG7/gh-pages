# Helm Chart Operations for CI/CD

Here are some common Helm operations you might use in a CI/CD pipeline:

1. **Add your Helm repository**
   ```bash
   helm repo add myrepo https://yourusername.github.io/your-repo-name/
   ```

2. **Update the repository**
   ```bash
   helm repo update
   ```

3. **Search for charts in your repository**
   ```bash
   helm search repo myrepo
   ```

4. **Install a chart**
   ```bash
   helm install my-release myrepo/chart-name
   ```

5. **Upgrade a release**
   ```bash
   helm upgrade my-release myrepo/chart-name
   ```

6. **Rollback a release**
   ```bash
   helm rollback my-release 1
   ```

7. **Uninstall a release**
   ```bash
   helm uninstall my-release
   ```

8. **List all releases**
   ```bash
   helm list
   ```

9. **Get release status**
   ```bash
   helm status my-release
   ```

10. **Get release history**
    ```bash
    helm history my-release
    ```

11. **Package a chart**
    ```bash
    helm package ./charts/my-chart
    ```

12. **Lint a chart**
    ```bash
    helm lint ./charts/my-chart
    ```

