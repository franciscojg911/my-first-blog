# Crear un entorno virtual:
mkdir {carpeta1}
cd {carpeta1}
> estando dentro de {carpeta1}
python3 -m venv {entorno_virtual}
> estando dentro de {carpeta1}
{entorno_virtual}\Scripts\activate

# Instalar django
>> iniciado el {entorno_virtual}

python -m pip install --upgrade pip

> generar archivo:
{carpeta1}/requirements.txt:
Django~=2.2.4

pip install -r requirements.txt

# 