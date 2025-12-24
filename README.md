# newrelic

Install newrelic-cli on linux:
```bash
curl -Ls https://download.newrelic.com/install/newrelic-cli/scripts/install.sh | bash
```

Install newrelic-cli on macos:
```bash
brew install newrelic-cli
```

---

Become root user:
```bash
sudo -i
```

Add new profile:
```bash
newrelic profiles add --profile shubham
```

Set profile as default:
```bash
newrelic profiles default --profile shubham
```

Install newrelic agent:
```bash
newrelic install
```

---

Add helm repo
```bash
helm repo add newrelic https://helm-charts.newrelic.com
```







