**download da versão mais recente do kubectl usando o seguinte comando:**
curl -LO "[5](https://dl.k8s.io/release/)$ (curl -L -s [6](https://dl.k8s.io/release/stable.txt%29/bin/linux/amd64/kubectl)"

**Se você deseja baixar uma versão específica, substitua a parte** $ (curl -L -s [7](https://dl.k8s.io/release/stable.txt%29) pelo número da versão desejada.
**Por exemplo, para a versão 1.29.1, use:**
curl -LO [8](https://dl.k8s.io/release/v1.29.1/bin/linux/amd64/kubectl)


**Instalação Kind**

# Para AMD64 / x86_64
[ $(uname -m) = x86_64 ] && curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.21.0/kind-linux-amd64
chmod +x ./kind
sudo mv ./kind /usr/local/bin/kind

**versão do Kind**
kind version

**criar um cluster com kind**
kind create cluster
