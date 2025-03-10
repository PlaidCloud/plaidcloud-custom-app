# A Hello World Example for PlaidCloud Custom App Deployment

This repository contains an example of a hello world app that will deploy as part of a PlaidCloud workspace.

To deploy a custom application, follow the steps below:

## 1. Fork this repository

## 2. Create your helm templates or update the existing ones in the example

The templates provided will deploy a basic application on the PlaidCloud stack.

As an interested party you will at minimum want to replace the image contained within the deployment-example.yaml file

```yaml
      containers:
      - name: example-hello
        image: nginxdemos/hello:0.4
```

If your image repository is private, we have included an example of how to create an image pull secret.

## 3. Update the values file and Chart with your values and application information

## 4. Notify your technical support member to add the custom application to your workspace
