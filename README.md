# Trivy
**What is trivy**


Trivy is an open-source vulnerability scanner that can detect vulnerabilities in containers, file systems, Git repositories, and more

**How to install Trivy in Ubuntu Os**


sudo apt-get install wget apt-transport-https gnupg lsb-release
wget -qO - https://aquasecurity.github.io/trivy-repo/deb/public.key | sudo apt-key add -
echo deb https://aquasecurity.github.io/trivy-repo/deb $(lsb_release -sc) main | sudo tee -a /etc/apt/sources.list.d/trivy.list
sudo apt-get update
sudo apt-get install trivy

**trivy commands**


trivy fs --format table -o trivy-scaner-report.html

