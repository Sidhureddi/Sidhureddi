
-----> Building on the Heroku-22 stack
-----> Using buildpacks:
       1. https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
       2. heroku/python
-----> ffmpeg app detected

-----> Installing ffmpeg
       Variable FFMPEG_DOWNLOAD_URL isn't set, using default value
       Downloading https://johnvansickle.com/ffmpeg/builds/ffmpeg-git-amd64-static.tar.xz
       Unpacking the archive
       Installation successful
-----> Python app detected
-----> Using Python version specified in runtime.txt
 !     
 !     A Python security update is available! Upgrade as soon as possible to: python-3.10.8
 !     See: https://devcenter.heroku.com/articles/python-runtimes
 !     
-----> Installing python-3.10.4
-----> Installing pip 22.3.1, setuptools 63.4.3 and wheel 0.37.1
-----> Installing SQLite3
-----> Installing requirements with pip
       Collecting numpy
         Downloading numpy-1.23.5-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (17.1 MB)
       Collecting Pillow
         Downloading Pillow-9.3.0-cp310-cp310-manylinux_2_28_x86_64.whl (3.3 MB)
       Collecting yt-dlp
         Downloading yt_dlp-2022.11.11-py2.py3-none-any.whl (2.8 MB)
       Collecting aiohttp
         Downloading aiohttp-3.8.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.0 MB)
       Collecting hachoir
         Downloading hachoir-3.1.3-py3-none-any.whl (647 kB)
       Collecting olefile
         Downloading olefile-0.46.zip (112 kB)
         Preparing metadata (setup.py): started
         Preparing metadata (setup.py): finished with status 'done'
       Collecting requests
         Downloading requests-2.28.1-py3-none-any.whl (62 kB)
       Collecting tgcrypto
         Downloading TgCrypto-1.2.5-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (59 kB)
       Collecting aiofiles
         Downloading aiofiles-22.1.0-py3-none-any.whl (14 kB)
       Collecting dnspython
         Downloading dnspython-2.2.1-py3-none-any.whl (269 kB)
       Collecting motor[srv]
         Downloading motor-3.1.1-py3-none-any.whl (56 kB)
       Collecting beautifulsoup4
         Downloading beautifulsoup4-4.11.1-py3-none-any.whl (128 kB)
       Collecting pyrogram==1.4.16
         Downloading Pyrogram-1.4.16-py3-none-any.whl (3.1 MB)
       Collecting pysocks==1.7.1
         Downloading PySocks-1.7.1-py3-none-any.whl (16 kB)
       Collecting pyaes==1.6.1
         Downloading pyaes-1.6.1.tar.gz (28 kB)
         Preparing metadata (setup.py): started
         Preparing metadata (setup.py): finished with status 'done'
       Collecting websockets
         Downloading websockets-10.4-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (106 kB)
       Collecting pycryptodomex
         Downloading pycryptodomex-3.15.0-cp35-abi3-manylinux2010_x86_64.whl (2.3 MB)
       Collecting mutagen
         Downloading mutagen-1.46.0-py3-none-any.whl (193 kB)
       Collecting certifi
         Downloading certifi-2022.9.24-py3-none-any.whl (161 kB)
       Collecting brotli
         Downloading Brotli-1.0.9-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl (2.7 MB)
       Collecting frozenlist>=1.1.1
         Downloading frozenlist-1.3.3-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (149 kB)
       Collecting multidict<7.0,>=4.5
         Downloading multidict-6.0.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (114 kB)
       Collecting async-timeout<5.0,>=4.0.0a3
         Downloading async_timeout-4.0.2-py3-none-any.whl (5.8 kB)
       Collecting yarl<2.0,>=1.0
         Downloading yarl-1.8.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (263 kB)
       Collecting attrs>=17.3.0
         Downloading attrs-22.1.0-py2.py3-none-any.whl (58 kB)
       Collecting aiosignal>=1.1.2
         Downloading aiosignal-1.3.1-py3-none-any.whl (7.6 kB)
       Collecting charset-normalizer<3.0,>=2.0
         Downloading charset_normalizer-2.1.1-py3-none-any.whl (39 kB)
       Collecting urllib3<1.27,>=1.21.1
         Downloading urllib3-1.26.12-py2.py3-none-any.whl (140 kB)
       Collecting idna<4,>=2.5
         Downloading idna-3.4-py3-none-any.whl (61 kB)
       Collecting pymongo<5,>=4.1
         Downloading pymongo-4.3.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (492 kB)
       Collecting soupsieve>1.2
         Downloading soupsieve-2.3.2.post1-py3-none-any.whl (37 kB)
       Building wheels for collected packages: pyaes, olefile
         Building wheel for pyaes (setup.py): started
         Building wheel for pyaes (setup.py): finished with status 'done'
         Created wheel for pyaes: filename=pyaes-1.6.1-py3-none-any.whl size=26347 sha256=712085cad131029abde419d02bf45c53be575d4339686c85f4ab763a8f2938e6
         Stored in directory: /tmp/pip-ephem-wheel-cache-f9a4s90t/wheels/60/9b/97/e53da26f9cc31f82f8c9bf9870328e72888be92cc4660f4a06
         Building wheel for olefile (setup.py): started
         Building wheel for olefile (setup.py): finished with status 'done'
         Created wheel for olefile: filename=olefile-0.46-py2.py3-none-any.whl size=35415 sha256=8bd479b38cc257f8343578b917f9f70e34eec35f637b0c16c50414f810b0ab4a
         Stored in directory: /tmp/pip-ephem-wheel-cache-f9a4s90t/wheels/4d/df/7b/24b97ee860e26da4f0b8867775ee4d94a5e8a0d173484ee74c
       Successfully built pyaes olefile
       Installing collected packages: pyaes, hachoir, brotli, websockets, urllib3, tgcrypto, soupsieve, pysocks, pycryptodomex, Pillow, olefile, numpy, mutagen, multidict, idna, frozenlist, dnspython, charset-normalizer, certifi, attrs, async-timeout, aiofiles, yt-dlp, yarl, requests, pyrogram, pymongo, beautifulsoup4, aiosignal, motor, aiohttp
       Successfully installed Pillow-9.3.0 aiofiles-22.1.0 aiohttp-3.8.3 aiosignal-1.3.1 async-timeout-4.0.2 attrs-22.1.0 beautifulsoup4-4.11.1 brotli-1.0.9 certifi-2022.9.24 charset-normalizer-2.1.1 dnspython-2.2.1 frozenlist-1.3.3 hachoir-3.1.3 idna-3.4 motor-3.1.1 multidict-6.0.2 mutagen-1.46.0 numpy-1.23.5 olefile-0.46 pyaes-1.6.1 pycryptodomex-3.15.0 pymongo-4.3.3 pyrogram-1.4.16 pysocks-1.7.1 requests-2.28.1 soupsieve-2.3.2.post1 tgcrypto-1.2.5 urllib3-1.26.12 websockets-10.4 yarl-1.8.1 yt-dlp-2022.11.11
-----> Discovering process types
       Procfile declares types -> worker

-----> Compressing...
       Done: 116.6M
-----> Launching...
       Released v4
       https://qualityanswers.herokuapp.com/ deployed to Heroku

[34mStarting November 28th, 2022, free Heroku Dynos, free Heroku Postgres, and free Heroku Data for RedisÂ® will no longer be available.[0m

[34mIf you have apps using any of these resources, you must upgrade to paid plans by this date to ensure your apps continue to run and to retain your data. For students, we will announce a new program by the end of September. Learn more at https://blog.heroku.com/next-chapter[0m
