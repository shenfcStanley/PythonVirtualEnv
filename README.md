# PythonVirtualEnv

1. download anaconda and install it to a specific directory
2. in PyCharm, go to preference->project intepreter->add local->Conda Environment, choose the installed anaconda as interpreter.
3. Sometimes we can install a smaller environment. In command line, type "conda create --name your_env_name python=3.5".
4. Use command "conda activate your_env_name" to activate the environment, use command "conda deactivate" to deactivate it.
5. then we can install package diretly use command, such as "conda install tensorflow"
6. Go to pycharm, go to preference->project intepreter->add local->Conda Environment, choose the installed anaconda new env as interpreter. Directory is "~/anaconda3/envs/xxx/bin/python"
7. Since we already created the environment, so in PyCharm, we chooose existing environment, and go to find the python executable file under directory "~/anaconda3/envs/xxx/bin/python".


# Open Jupyter with Anaconda env

1. Go to your developed env: conda activate your_env_name
2. conda install ipykernel
3. ipython kernel install --user --name=<any_name_for_kernel>, after this, system will create a new kernel directory under "/Users/m102853/Library/Jupyter/kernels/<any_name_for_kernel>"
4. Then in notebook, you can test your sys path by using "sys.executable"
