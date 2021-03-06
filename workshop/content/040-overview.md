---
Title: Application overview
PrevPage: 030-deploy-an-app
NextPage: 050-creating-an-application
---

In this course you will get a __deep__ introduction to the tool ``odo``. This tool provides a simplified command line client for deploying applications to OpenShift.

The goal for this lab is to showcase `odo` and all of it's primitives and to do so we're going to use a sample application. Don't judge the code for this sample application as it has been developed just for training purposes.

Now although the intent is to show as much as possible of what `odo` can do, because of how the workshop environment works, we have skipped how you can login to OpenShift using `odo`. In the workshop environment, you have already been logged in from the terminal window. You also have a project created for you in advance.

If you were using `odo` with your own cluster, you could login to the cluster by using:

```bash
odo login
```

The command will interactively prompt you for details of the cluster. Alternatively you could supply the address of the OpenShift cluster as an argument.

To create, change or delete projects, you can use the `odo project` command. Run this with no additional arguments and it will show you the name of the current project you are working in.

```execute
odo project
```

To see other operations you can perform on projects, run:

```execute
odo project --help
```

The `--help` option can be used on any `odo` command to see more details about what it can do.

Since we already have a project created for us, we are good to go though, and do not need to create one.
