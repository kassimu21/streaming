HOW TO SET UP A LIVE STREAMING APP
Create a GitHub Account if you dont have one
download and install Visual Studio Code
Download and Install NodeJS
Download and install Phython
Download and install Git
Downloa the streaming apps from this GitHub page
Right click on the downloaded folder and click on open with Command Promt
follow the below command on the VS Code terminal (anything that has not been downloaded automatically download it manually)
after the intallation hold the CTRL Key and click on localhost:80000 on the left panel of the VS Code
You need to create an account on clouadflare and register for a domain name before a client can view the live stream

C:\Users\toacu\OneDrive\Documentos\streaming-main>
C:\Users\toacu\OneDrive\Documentos\streaming-main>python -m venv venv

C:\Users\toacu\OneDrive\Documentos\streaming-main>venv\Scripts\activate               

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>pip install -r requirements.txt
Collecting blinker==1.9.0 (from -r requirements.txt (line 1))
  Downloading blinker-1.9.0-py3-none-any.whl.metadata (1.6 kB)
Collecting certifi==2025.8.3 (from -r requirements.txt (line 2))
  Downloading certifi-2025.8.3-py3-none-any.whl.metadata (2.4 kB)
Collecting charset-normalizer==3.4.3 (from -r requirements.txt (line 3))
  Downloading charset_normalizer-3.4.3-cp314-cp314-win_amd64.whl.metadata (37 kB)
Collecting click==8.2.1 (from -r requirements.txt (line 4))
  Downloading click-8.2.1-py3-none-any.whl.metadata (2.5 kB)
Collecting colorama==0.4.6 (from -r requirements.txt (line 5))
  Downloading colorama-0.4.6-py2.py3-none-any.whl.metadata (17 kB)
Collecting contourpy==1.3.3 (from -r requirements.txt (line 6))
  Downloading contourpy-1.3.3-cp314-cp314-win_amd64.whl.metadata (5.5 kB)
Collecting cycler==0.12.1 (from -r requirements.txt (line 7))
  Downloading cycler-0.12.1-py3-none-any.whl.metadata (3.8 kB)
Collecting filelock==3.19.1 (from -r requirements.txt (line 8))
  Downloading filelock-3.19.1-py3-none-any.whl.metadata (2.1 kB)
Collecting Flask==3.1.2 (from -r requirements.txt (line 9))
  Downloading flask-3.1.2-py3-none-any.whl.metadata (3.2 kB)
Collecting fonttools==4.59.1 (from -r requirements.txt (line 10))
  Downloading fonttools-4.59.1-cp314-cp314-win_amd64.whl.metadata (111 kB)
Collecting fsspec==2025.7.0 (from -r requirements.txt (line 11))
  Downloading fsspec-2025.7.0-py3-none-any.whl.metadata (12 kB)
Collecting idna==3.10 (from -r requirements.txt (line 12))
  Downloading idna-3.10-py3-none-any.whl.metadata (10 kB)
Collecting itsdangerous==2.2.0 (from -r requirements.txt (line 13))
  Downloading itsdangerous-2.2.0-py3-none-any.whl.metadata (1.9 kB)
Collecting Jinja2==3.1.6 (from -r requirements.txt (line 14))
  Downloading jinja2-3.1.6-py3-none-any.whl.metadata (2.9 kB)
Collecting kiwisolver==1.4.9 (from -r requirements.txt (line 15))
  Downloading kiwisolver-1.4.9-cp314-cp314-win_amd64.whl.metadata (6.4 kB)
Collecting MarkupSafe==3.0.2 (from -r requirements.txt (line 16))
  Downloading markupsafe-3.0.2.tar.gz (20 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting matplotlib==3.10.5 (from -r requirements.txt (line 17))
  Downloading matplotlib-3.10.5-cp314-cp314-win_amd64.whl.metadata (11 kB)
Collecting mpmath==1.3.0 (from -r requirements.txt (line 18))
  Downloading mpmath-1.3.0-py3-none-any.whl.metadata (8.6 kB)
Collecting networkx==3.5 (from -r requirements.txt (line 19))
  Downloading networkx-3.5-py3-none-any.whl.metadata (6.3 kB)
Collecting numpy==2.2.6 (from -r requirements.txt (line 20))
  Downloading numpy-2.2.6.tar.gz (20.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 20.3/20.3 MB 1.1 MB/s  0:00:19
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... error
  error: subprocess-exited-with-error
  
  × Preparing metadata (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [21 lines of output]
      + C:\Users\toacu\OneDrive\Documentos\streaming-main\venv\Scripts\python.exe C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a\vendored-meson\meson\meson.py setup C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a\.mesonpy-1qjplkm3 -Dbuildtype=release -Db_ndebug=if-release -Db_vscrt=md --native-file=C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a\.mesonpy-1qjplkm3\meson-python-native-file.ini
      The Meson build system
      Version: 1.5.2
      Source dir: C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a
      Build dir: C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a\.mesonpy-1qjplkm3
      Build type: native build
      Project name: NumPy
      Project version: 2.2.6
      WARNING: Failed to activate VS environment: Could not parse vswhere.exe output
      
      ..\meson.build:1:0: ERROR: Unknown compiler(s): [['icl'], ['cl'], ['cc'], ['gcc'], ['clang'], ['clang-cl'], ['pgcc']]
      The following exception(s) were encountered:
      Running `icl ""` gave "[WinError 2] The system cannot find the file specified"
      Running `cl /?` gave "[WinError 2] The system cannot find the file specified"
      Running `cc --version` gave "[WinError 2] The system cannot find the file specified"
      Running `gcc --version` gave "[WinError 2] The system cannot find the file specified"
      Running `clang --version` gave "[WinError 2] The system cannot find the file specified"
      Running `clang-cl /?` gave "[WinError 2] The system cannot find the file specified"
      Running `pgcc --version` gave "[WinError 2] The system cannot find the file specified"
      
      A full log can be found at C:\Users\toacu\AppData\Local\Temp\pip-install-vcyoaa1w\numpy_6c7f60d29d7148d987d6edd82ea7903a\.mesonpy-1qjplkm3\meson-logs\meson-log.txt
      [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
error: metadata-generation-failed

× Encountered error while generating package metadata.
╰─> numpy

note: This is an issue with the package mentioned above, not pip.
hint: See above for details.

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>python app.py
Traceback (most recent call last):
  File "C:\Users\toacu\OneDrive\Documentos\streaming-main\app.py", line 1, in <module>
    from flask import Flask, render_template, request, Response, session, redirect, url_for, jsonify, abort, send_from_directory
ModuleNotFoundError: No module named 'flask'

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>pip install flask            
Collecting flask
  Downloading flask-3.1.3-py3-none-any.whl.metadata (3.2 kB)
Collecting blinker>=1.9.0 (from flask)
  Using cached blinker-1.9.0-py3-none-any.whl.metadata (1.6 kB)
Collecting click>=8.1.3 (from flask)
  Downloading click-8.4.1-py3-none-any.whl.metadata (2.6 kB)
Collecting itsdangerous>=2.2.0 (from flask)
  Using cached itsdangerous-2.2.0-py3-none-any.whl.metadata (1.9 kB)
Collecting jinja2>=3.1.2 (from flask)
  Using cached jinja2-3.1.6-py3-none-any.whl.metadata (2.9 kB)
Collecting markupsafe>=2.1.1 (from flask)
  Downloading markupsafe-3.0.3-cp314-cp314-win_amd64.whl.metadata (2.8 kB)
Collecting werkzeug>=3.1.0 (from flask)
  Downloading werkzeug-3.1.8-py3-none-any.whl.metadata (4.0 kB)
Collecting colorama (from click>=8.1.3->flask)
  Using cached colorama-0.4.6-py2.py3-none-any.whl.metadata (17 kB)
Downloading flask-3.1.3-py3-none-any.whl (103 kB)
Downloading blinker-1.9.0-py3-none-any.whl (8.5 kB)
Downloading click-8.4.1-py3-none-any.whl (116 kB)
Downloading itsdangerous-2.2.0-py3-none-any.whl (16 kB)
Downloading jinja2-3.1.6-py3-none-any.whl (134 kB)
Downloading markupsafe-3.0.3-cp314-cp314-win_amd64.whl (15 kB)
Downloading werkzeug-3.1.8-py3-none-any.whl (226 kB)
Downloading colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Installing collected packages: markupsafe, itsdangerous, colorama, blinker, werkzeug, jinja2, click, flask
Successfully installed blinker-1.9.0 click-8.4.1 colorama-0.4.6 flask-3.1.3 itsdangerous-2.2.0 jinja2-3.1.6 markupsafe-3.0.3 werkzeug-3.1.8

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>python app.py
Traceback (most recent call last):
  File "C:\Users\toacu\OneDrive\Documentos\streaming-main\app.py", line 3, in <module>
    import cv2
ModuleNotFoundError: No module named 'cv2'

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>pip install opencv-python
Collecting opencv-python
  Downloading opencv_python-4.13.0.92-cp37-abi3-win_amd64.whl.metadata (20 kB)
Collecting numpy>=2 (from opencv-python)
  Downloading numpy-2.4.6-cp314-cp314-win_amd64.whl.metadata (6.6 kB)
Downloading opencv_python-4.13.0.92-cp37-abi3-win_amd64.whl (40.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 40.2/40.2 MB 555.8 kB/s  0:01:04
Downloading numpy-2.4.6-cp314-cp314-win_amd64.whl (12.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 12.5/12.5 MB 647.6 kB/s  0:00:19
Installing collected packages: numpy, opencv-python
Successfully installed numpy-2.4.6 opencv-python-4.13.0.92

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>python app.py            
Traceback (most recent call last):
  File "C:\Users\toacu\OneDrive\Documentos\streaming-main\app.py", line 4, in <module>
    from ultralytics import YOLO
ModuleNotFoundError: No module named 'ultralytics'

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>pip install ultralytics
Collecting ultralytics
  Downloading ultralytics-8.4.53-py3-none-any.whl.metadata (39 kB)
Requirement already satisfied: numpy>=1.23.0 in .\venv\Lib\site-packages (from ultralytics) (2.4.6)
Collecting matplotlib>=3.3.0 (from ultralytics)
  Downloading matplotlib-3.10.9-cp314-cp314-win_amd64.whl.metadata (52 kB)
Requirement already satisfied: opencv-python>=4.6.0 in .\venv\Lib\site-packages (from ultralytics) (4.13.0.92)
Collecting pillow>=7.1.2 (from ultralytics)
  Downloading pillow-12.2.0-cp314-cp314-win_amd64.whl.metadata (9.0 kB)
Collecting pyyaml>=5.3.1 (from ultralytics)
  Downloading pyyaml-6.0.3-cp314-cp314-win_amd64.whl.metadata (2.4 kB)
Collecting requests>=2.23.0 (from ultralytics)
  Downloading requests-2.34.2-py3-none-any.whl.metadata (4.8 kB)
Collecting scipy>=1.4.1 (from ultralytics)
  Downloading scipy-1.17.1-cp314-cp314-win_amd64.whl.metadata (60 kB)
Collecting torch>=1.8.0 (from ultralytics)
  Downloading torch-2.12.0-cp314-cp314-win_amd64.whl.metadata (31 kB)
Collecting torchvision>=0.9.0 (from ultralytics)
  Downloading torchvision-0.27.0-cp314-cp314-win_amd64.whl.metadata (5.5 kB)
Collecting psutil>=5.8.0 (from ultralytics)
  Downloading psutil-7.2.2-cp37-abi3-win_amd64.whl.metadata (22 kB)
Collecting polars>=0.20.0 (from ultralytics)
  Downloading polars-1.41.0-py3-none-any.whl.metadata (10 kB)
Collecting ultralytics-thop>=2.0.18 (from ultralytics)
  Downloading ultralytics_thop-2.0.19-py3-none-any.whl.metadata (14 kB)
Collecting contourpy>=1.0.1 (from matplotlib>=3.3.0->ultralytics)
  Using cached contourpy-1.3.3-cp314-cp314-win_amd64.whl.metadata (5.5 kB)
Collecting cycler>=0.10 (from matplotlib>=3.3.0->ultralytics)
  Using cached cycler-0.12.1-py3-none-any.whl.metadata (3.8 kB)
Collecting fonttools>=4.22.0 (from matplotlib>=3.3.0->ultralytics)
  Downloading fonttools-4.63.0-cp314-cp314-win_amd64.whl.metadata (121 kB)
Collecting kiwisolver>=1.3.1 (from matplotlib>=3.3.0->ultralytics)
  Downloading kiwisolver-1.5.0-cp314-cp314-win_amd64.whl.metadata (5.2 kB)
Collecting packaging>=20.0 (from matplotlib>=3.3.0->ultralytics)
  Using cached packaging-26.2-py3-none-any.whl.metadata (3.5 kB)
Collecting pyparsing>=3 (from matplotlib>=3.3.0->ultralytics)
  Downloading pyparsing-3.3.2-py3-none-any.whl.metadata (5.8 kB)
Collecting python-dateutil>=2.7 (from matplotlib>=3.3.0->ultralytics)
  Downloading python_dateutil-2.9.0.post0-py2.py3-none-any.whl.metadata (8.4 kB)
Collecting polars-runtime-32==1.41.0 (from polars>=0.20.0->ultralytics)
  Downloading polars_runtime_32-1.41.0-cp310-abi3-win_amd64.whl.metadata (1.5 kB)
Collecting six>=1.5 (from python-dateutil>=2.7->matplotlib>=3.3.0->ultralytics)
  Downloading six-1.17.0-py2.py3-none-any.whl.metadata (1.7 kB)
Collecting charset_normalizer<4,>=2 (from requests>=2.23.0->ultralytics)
  Downloading charset_normalizer-3.4.7-cp314-cp314-win_amd64.whl.metadata (41 kB)
Collecting idna<4,>=2.5 (from requests>=2.23.0->ultralytics)
  Downloading idna-3.16-py3-none-any.whl.metadata (6.4 kB)
Collecting urllib3<3,>=1.26 (from requests>=2.23.0->ultralytics)
  Downloading urllib3-2.7.0-py3-none-any.whl.metadata (6.9 kB)
Collecting certifi>=2023.5.7 (from requests>=2.23.0->ultralytics)
  Downloading certifi-2026.5.20-py3-none-any.whl.metadata (2.5 kB)
Collecting filelock (from torch>=1.8.0->ultralytics)
  Downloading filelock-3.29.0-py3-none-any.whl.metadata (2.0 kB)
Collecting typing-extensions>=4.10.0 (from torch>=1.8.0->ultralytics)
  Downloading typing_extensions-4.15.0-py3-none-any.whl.metadata (3.3 kB)
Collecting setuptools<82 (from torch>=1.8.0->ultralytics)
  Downloading setuptools-81.0.0-py3-none-any.whl.metadata (6.6 kB)
Collecting sympy>=1.13.3 (from torch>=1.8.0->ultralytics)
  Downloading sympy-1.14.0-py3-none-any.whl.metadata (12 kB)
Collecting networkx>=2.5.1 (from torch>=1.8.0->ultralytics)
  Downloading networkx-3.6.1-py3-none-any.whl.metadata (6.8 kB)
Requirement already satisfied: jinja2 in .\venv\Lib\site-packages (from torch>=1.8.0->ultralytics) (3.1.6)
Collecting fsspec>=0.8.5 (from torch>=1.8.0->ultralytics)
  Downloading fsspec-2026.4.0-py3-none-any.whl.metadata (10 kB)
Collecting mpmath<1.4,>=1.1.0 (from sympy>=1.13.3->torch>=1.8.0->ultralytics)
  Using cached mpmath-1.3.0-py3-none-any.whl.metadata (8.6 kB)
Requirement already satisfied: MarkupSafe>=2.0 in .\venv\Lib\site-packages (from jinja2->torch>=1.8.0->ultralytics) (3.0.3)
Downloading ultralytics-8.4.53-py3-none-any.whl (1.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.3/1.3 MB 423.1 kB/s  0:00:02
Downloading matplotlib-3.10.9-cp314-cp314-win_amd64.whl (8.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.3/8.3 MB 338.8 kB/s  0:00:24
Downloading contourpy-1.3.3-cp314-cp314-win_amd64.whl (232 kB)
Downloading cycler-0.12.1-py3-none-any.whl (8.3 kB)
Downloading fonttools-4.63.0-cp314-cp314-win_amd64.whl (2.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 457.6 kB/s  0:00:04
Downloading kiwisolver-1.5.0-cp314-cp314-win_amd64.whl (75 kB)
Using cached packaging-26.2-py3-none-any.whl (100 kB)
Downloading pillow-12.2.0-cp314-cp314-win_amd64.whl (7.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.2/7.2 MB 597.0 kB/s  0:00:12
Downloading polars-1.41.0-py3-none-any.whl (832 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 833.0/833.0 kB 604.4 kB/s  0:00:01
Downloading polars_runtime_32-1.41.0-cp310-abi3-win_amd64.whl (51.9 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 51.9/51.9 MB 355.1 kB/s  0:02:26
Downloading psutil-7.2.2-cp37-abi3-win_amd64.whl (137 kB)
Downloading pyparsing-3.3.2-py3-none-any.whl (122 kB)
Downloading python_dateutil-2.9.0.post0-py2.py3-none-any.whl (229 kB)
Downloading pyyaml-6.0.3-cp314-cp314-win_amd64.whl (156 kB)
Downloading requests-2.34.2-py3-none-any.whl (73 kB)
Downloading charset_normalizer-3.4.7-cp314-cp314-win_amd64.whl (159 kB)
Downloading idna-3.16-py3-none-any.whl (74 kB)
Downloading urllib3-2.7.0-py3-none-any.whl (131 kB)
Downloading certifi-2026.5.20-py3-none-any.whl (134 kB)
Downloading scipy-1.17.1-cp314-cp314-win_amd64.whl (37.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 37.3/37.3 MB 501.9 kB/s  0:01:19
Downloading six-1.17.0-py2.py3-none-any.whl (11 kB)
Downloading torch-2.12.0-cp314-cp314-win_amd64.whl (123.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 123.0/123.0 MB 788.6 kB/s  0:03:20
Downloading setuptools-81.0.0-py3-none-any.whl (1.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 308.1 kB/s  0:00:03
Downloading fsspec-2026.4.0-py3-none-any.whl (203 kB)
Downloading networkx-3.6.1-py3-none-any.whl (2.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 449.8 kB/s  0:00:04
Downloading sympy-1.14.0-py3-none-any.whl (6.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 6.3/6.3 MB 884.5 kB/s  0:00:07
Downloading mpmath-1.3.0-py3-none-any.whl (536 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 536.2/536.2 kB 1.9 MB/s  0:00:00
Downloading torchvision-0.27.0-cp314-cp314-win_amd64.whl (4.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.1/4.1 MB 1.6 MB/s  0:00:02
Downloading typing_extensions-4.15.0-py3-none-any.whl (44 kB)
Downloading ultralytics_thop-2.0.19-py3-none-any.whl (28 kB)
Downloading filelock-3.29.0-py3-none-any.whl (39 kB)
Installing collected packages: mpmath, urllib3, typing-extensions, sympy, six, setuptools, scipy, pyyaml, pyparsing, psutil, polars-runtime-32, pillow, packaging, networkx, kiwisolver, idna, fsspec, fonttools, filelock, cycler, contourpy, charset_normalizer, certifi, torch, requests, python-dateutil, polars, ultralytics-thop, torchvision, matplotlib, ultralytics
Successfully installed certifi-2026.5.20 charset_normalizer-3.4.7 contourpy-1.3.3 cycler-0.12.1 filelock-3.29.0 fonttools-4.63.0 fsspec-2026.4.0 idna-3.16 kiwisolver-1.5.0 matplotlib-3.10.9 mpmath-1.3.0 networkx-3.6.1 packaging-26.2 pillow-12.2.0 polars-1.41.0 polars-runtime-32-1.41.0 psutil-7.2.2 pyparsing-3.3.2 python-dateutil-2.9.0.post0 pyyaml-6.0.3 requests-2.34.2 scipy-1.17.1 setuptools-81.0.0 six-1.17.0 sympy-1.14.0 torch-2.12.0 torchvision-0.27.0 typing-extensions-4.15.0 ultralytics-8.4.53 ultralytics-thop-2.0.19 urllib3-2.7.0

(venv) C:\Users\toacu\OneDrive\Documentos\streaming-main>python app.py
Creating new Ultralytics Settings v0.0.6 file  
View Ultralytics Settings with 'yolo settings' or at 'C:\Users\toacu\AppData\Roaming\Ultralytics\settings.json'
Update Settings with 'yolo settings key=value', i.e. 'yolo settings runs_dir=path/to/dir'. For help see https://docs.ultralytics.com/quickstart/#ultralytics-settings.
2026-05-23 13:12:03,124 - __main__ - INFO - Starting Flask app initialization
2026-05-23 13:12:03,125 - __main__ - WARNING - Using fallback ephemeral secret key. Set FLASK_SECRET_KEY in production.
2026-05-23 13:12:03,126 - __main__ - INFO - Loading YOLO model
2026-05-23 13:12:03,160 - __main__ - INFO - YOLO model loaded successfully
2026-05-23 13:12:03,160 - __main__ - INFO - Flask app created
2026-05-23 13:12:03,161 - __main__ - WARNING - Using default admin credentials. Set APP_ADMIN_USER and APP_ADMIN_PASS in production.
2026-05-23 13:12:03,162 - __main__ - INFO - Test route registered
 * Serving Flask app 'app'
 * Debug mode: off
2026-05-23 13:12:03,177 - werkzeug - INFO - WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:8000
 * Running on http://192.168.43.185:8000
2026-05-23 13:12:03,177 - werkzeug - INFO - Press CTRL+C to quit
2026-05-23 13:12:32,478 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:12:32] "GET / HTTP/1.1" 200 -
2026-05-23 13:12:32,550 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:12:32] "GET /assets/tailwind.min.js HTTP/1.1" 200 -
2026-05-23 13:12:32,725 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:12:32] "GET /favicon.ico HTTP/1.1" 404 -
2026-05-23 13:13:28,510 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:13:28] "POST /login HTTP/1.1" 302 -
2026-05-23 13:13:28,826 - __main__ - INFO - Loaded 3 cameras from file
2026-05-23 13:13:28,837 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:13:28] "GET /dashboard HTTP/1.1" 200 -
2026-05-23 13:13:28,845 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:13:28] "GET /assets/tailwind.min.js HTTP/1.1" 304 -
2026-05-23 13:13:53,319 - __main__ - INFO - Loaded 3 cameras from file
2026-05-23 13:13:53,326 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:13:53] "GET /admin HTTP/1.1" 200 -
2026-05-23 13:13:53,626 - werkzeug - INFO - 127.0.0.1 - - [23/May/2026 13:13:53] "GET /assets/tailwind.min.js HTTP/1.1" 304 -
