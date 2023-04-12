<pre>
# My Django Project

This is a Django project with some specific dependencies. Follow the steps below to set up the project on your local machine.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/gdimoo/connerstone_django.git
```

2. Change to the project directory:

```bash
cd your_repository
```

3. (Optional) If you are using a conda environment, create and activate a new environment:

```bash
conda create --name my_new_env python=3.8
conda activate my_new_env
```

4. Install the required packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Running the Django server

1. Apply the migrations:

```bash
python manage.py migrate
```

2. Start the Django development server:

```bash
python manage.py runserver
```

3. Open your web browser and navigate to `http://127.0.0.1:8000/` to view the project.

## Deactivating the environment

If you are using a conda environment and want to deactivate it after you're done, run:

```bash
conda deactivate
```

</pre>
