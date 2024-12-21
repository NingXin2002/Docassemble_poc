# Docassemble_poc
Docassemble任意文件读取漏洞(CVE-2024-27292)

 python Docassemble_poc.py -h                              

                ) (`-.            ) (`-.
         ( OO ).           ( OO ).
        (_/.  \_)-. ,-.-')(_/.  \_)-. ,-.-')
         \  `.'  /  |  |OO)\  `.'  /  |  |OO)
          \     /\  |  |  \ \     /\  |  |  \
           \   \ |  |  |(_/  \   \ |  |  |(_/
          .'    \_),|  |_.' .'    \_),|  |_.'
         /  .'.  \(_|  |   /  .'.  \(_|  |
        '--'   '--' `--'  '--'   '--' `--'

usage: Docassemble_poc.py [-h] [-u URL] [-f FILE]  

Docassemble任意文件读取漏洞(CVE-2024-27292)  

optional arguments:  
  -h, --help            show this help message and exit  
  -u URL, --url URL     添加url信息  
  -f FILE, --file FILE  添加txt文件  

example:  
    python3 Docassemble_poc.py -u http://xxxx.xxxx.xxxx.xxxx  
    python3 Docassemble_poc.py -f x_url.txt  
