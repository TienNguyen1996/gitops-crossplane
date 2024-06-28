addVar.yml: This file is to add image as environment variable
addDefaultResource.yml: This sample mutates any container in a Pod which doesn't specify memory or cpu requests to apply some sane defaults
synSecret.yml: This policy will copy a Secret called `regcred` which exists in the `default` Namespace to new Namespaces when they are created. It will also push updates to the copied Secrets should the source Secret be changed.
