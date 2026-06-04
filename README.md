## Installing Jupyter kernel

uv add pandas numpy ipykernel
uv run python -m ipykernel install --user --name=my-uv-env --display-name "Python (uv-env)"
Reload VSCode
Go to Python Notebook and select Kernel from Jupyter kernel
If you modified the kernel, do need to Restart kernel option, it will automatically fetch the new packages from uv environment