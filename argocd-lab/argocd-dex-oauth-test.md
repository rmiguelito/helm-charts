argocd-dex-oauth-test
https://argocd.local.io
https://argocd.local.io/api/dex/callback

Client ID
Ov23liJnuFn9g8anmS0a

Client secrets
55327e0ac9758674c15d9e40ffa8309d1f4b1a35

---

Started the OpenShift cluster.

The server is accessible via web console at:
  https://console-openshift-console.apps-crc.testing

Log in as administrator:
  Username: kubeadmin
  Password: aPfvp-Te5vM-aD6pg-HSaFM


---

apiVersion: argoproj.io/v1alpha1
kind: ArgoCD
metadata:
  name: argocd
spec:
  server:
    route:
      enabled: true