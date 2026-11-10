# TPE - Fundamentos de la Ciencia de Datos - Grupo 14

**Integrantes:** Juan Cruz Higuera, Jeremías Aguilar, Santiago Silva Salvatierra  
**Dataset:** Global Food & Nutrition Database (`data/dataset.csv`)  
**Notebook principal:** [`entrega-tpe.ipynb`](entrega-tpe.ipynb)

---

## Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/juancruzhiguera/tpe-fcd.git
cd tpe-fcd
```

### 2. Crear y activar el entorno virtual

- **Linux / macOS:**
  ```bash
  python3 -m venv venv-tpe
  source venv-tpe/bin/activate
  ```
- **Windows (PowerShell / CMD):**
  ```powershell
  python -m venv venv-tpe
  .\venv-tpe\Scripts\activate
  ```

### 3. Instalar dependencias y registrar el kernel
Con el entorno virtual activado:
```bash
pip install -r requirements.txt
python -m ipykernel install --user --name=venv-tpe --display-name "Python (venv-tpe)"
```

---

## Ejecución en VS Code

1. Abre el proyecto en VS Code (`code .`). Asegúrate de tener instalada la extensión oficial **Jupyter** (`ms-toolsai.jupyter`).
2. Abre [`entrega-tpe.ipynb`](entrega-tpe.ipynb).
3. En la esquina superior derecha, haz clic en **"Select Kernel"** y selecciona:
   - **Python Environments...** $\rightarrow$ `venv-tpe` (o **Jupyter Kernel...** $\rightarrow$ `Python (venv-tpe)`).
4. Ejecuta las celdas o pulsa **"Run All"**.

> **¿No aparece el kernel en la lista?**
> - Haz clic en **Select Kernel** $\rightarrow$ **Select Another Kernel...** $\rightarrow$ **Python Environments...** $\rightarrow$ **Enter interpreter path...** e introduce la ruta del entorno:
>   - **Linux / macOS:** `./venv-tpe/bin/python`
>   - **Windows:** `.\venv-tpe\Scripts\python.exe`
> - O recarga la ventana de VS Code: `Ctrl + Shift + P` (o `Cmd + Shift + P`) $\rightarrow$ `Developer: Reload Window`.
