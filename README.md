# Starter-Kit
Starter Kit for UofA robomasters

There are two ways to get up and running:

## [Anaconda Environment](doc/configure_via_anaconda.md) (recommended)
It is recommended because I am using conda. I cannot help you if you choose to use Docker.

Supported Sytems: Linux (CPU), Mac (CPU), Windows (CPU)     

| Pros                         | Cons                                               |
|------------------------------|----------------------------------------------------|
| More straight-forward to use | AWS or GPU support is not built in (have to do this yourself)              |
| More community support       | Implementation is local and OS specific            |
| More heavily adopted         |                                                    |

## Docker (not recommended)
If is not recommended because I don't know how to use it. I don't even add a tutorial to it.
I just want to have these two tables and convince you to use Conda.

Supported Systems : AWS (CPU, GPU), Linux (CPU), Mac (CPU), Windows (CPU)     

| Pros                                | Cons                                 |
|-------------------------------------|--------------------------------------|
| Configure once for all environments | More challenging to use              |
| AWS, GPU support                    | Less community support               |
| Practice with Docker              | Have to manage images and containers |
|                                     |                                      |

### Error when import plt for mac users
This is caused by different rendering back end of matplotlib.
Follow the instructions [here](https://stackoverflow.com/questions/21784641/installation-issue-with-matplotlib-python)