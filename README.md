# How to train YOLOv3 using Darknet on Colab 12GB-RAM GPU notebook and optimize the VM runtime load times

This repo contains the Google Colab Notebook from the blog post: [How to train YOLOv3 using Darknet on Colab 12GB-RAM GPU notebook and optimize the VM runtime load times](http://blog.ibanyez.info/blogs/coding/20190410-run-a-google-colab-notebook-to-train-yolov3-using-darknet-in/)

This Colab notebook will show you how to:

* Train a **Yolo v3** model using **Darknet** using the Colab **12GB-RAM GPU**.
* Turn Colab notebooks into an effective tool to work on real projects. Dealing with the handicap of a runtime that will **blow up every 12 hours** into the space!
  * Working directly from the files on your computer.
  * Configure your notebook to install everything you need and start training in about a minute (Tested using 550MB dataset). 
  * Receive your trained weights directly on your computer during the training. While the notebook is training you can check how it is going using your trained weights in your computer.

## Contribution

Feel free to open issues for anything you find on the notebook. If you want to contribute, that's great in the first place! :clap:. 

Process:
* First open an issue about what you want to work on.
* Follow the steps explained on the wrokflow below.

### Workflow and contribution
If you want to contribute to this repository follow the instructions below.

What you will need is your own copy of the project in your local environment. Then set the remote upstream to the original repository. 
This allow you to create branches in your repo to develop new features or fix some issues. Then, before opening a `pull request` you will be able to rebase your repo with the original repo to stay up to date of changes made on that repository. At this point you can open the `pull request` on Github.

* Fork this repository
* Clone your new repo in your local environment. `git clone https://github.com/[your user]/BestForDev-Backend.git` 
* Add the original project as a remote. Don't forget to move to the repo folder before executing this command. `git remote add upstream https://github.com/bestfordev/BestForDev-Backend.git`

#### Developing
To start modifying or adding code you need to create a new branch named `feature/my-new-feature` or `fix/my_fix`. You can do that with `git checkout -b feature/my-new-feature`

Commit your changes to your new branch. When finished, create a pull request from your branch.

#### Before opening a pull request or staying up to date to the original repo
While you are adding code to your repo is quite possible that the original repo has changes by other developers. Before opening a `pull request` or if you just want to stay up to date, follow the commands below.

```
$ git checkout develop
$ git pull upstream develop
$ git checkout feature/my-new-feature
$ git rebase develop
```

Now, you can push your code to your repo and open the `pull request`.

#### Pull Requests
In order to merge a PR, it will first go through a review process. Once it is approved, we will merge to the develop branch using the Squash button in github.

When using squash, all the commits will be squashed into one. The idea is to merge features/fixes as oppose of merging each individual commit. This helps when looking back in time for changes in the code base, and if the PR has a great comment, it's easier to know why that code was introduced.

Note: This workflow is based on the workflow used in [Coding coach community](https://github.com/Coding-Coach/coding-coach)

## About me

You can find the original post with more explanations about this notebook at [How to train YOLOv3 using Darknet framework and optimize the VM runtime load times](post link)

* You can visit my blog at [Dev-ibanyez.info](http://blog.ibanyex.info)
* You can get in touch with me on [Twitter](https://twitter.com/dav_ibanez)
* You can comment on the [dev.to post about this notebook ](PENDING)
