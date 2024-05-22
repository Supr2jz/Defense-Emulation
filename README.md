# Defense-Emulation

analise de memoria - kali 

[vol.py](http://vol.py) “arquivo artefato” imageinfo - ver do que se trata win xp (profile) (qando for o profile xp nao precisa passar profile depois do artefato no comando)

[vol.py](http://vol.py) “arquivo artefato”- pslist - lista os processos - ir atras de processos que nao sao nativos do windows (reader_sl.exe)

pid - numero do processo

processo PAI - sempre segunda fileira do processo suspeito

useragent-

[vol.py](http://vol.py) “arquivo artefato” memdump -numero do processo suspeito  - -dump-dir=

strings numero do processo suspeito.dmp | grep -i “user-agent”

strings numero do processo suspeito.dmp | grep -i “******” - no lugar do “***” podemos colocar qualquer palavra para procurar no arquivo para ver se acha alguma coisa

[Vol.py](http://Vol.py) -f “arquivo artefato” dllist | grep -i “Descryptor” - lista o processo pelo nome descrito no “” (descriptor)

[Vol.py](http://Vol.py) -f “arquivo artefato” p malfind “***”

[Vol.py](http://Vol.py) -f “arquivo artefato” consoles 

[Vol.py](http://Vol.py) -f “arquivo artefato” cmdline 

[Vol.py](http://Vol.py) -f “arquivo artefato” filescan | grep -i ******** 

[Vol.py](http://Vol.py) -f “arquivo artefato” dumpregistry —dump-dir=.

regripper - dump de memoria

- anaise de memoria Windows
    
    Registryreport 
    

c windows32 sisten32

analisar registro do usuario na maquina

- erunt para pegar o registro da maquina
- RegRipper3.0-Master - para ler os arquivos e gerar o txt dos processos e horarios, etc
- registry-report (mesma coisa)

dumpti-  coletador de Memoria

magnect ram-  coletador de Memoria

Anaise de disco - 

arquivos .ad1 - jogar no ftkimager para analise 

autopsy - New case - tudo padrao so colocar nome - finish - next - next - em select data sourch Path: selecionar o arquivo a ser analisado e avançar
![image](https://github.com/Supr2jz/Defense-Emulation/assets/124740255/19da85c4-7f23-4f5d-8486-1a0de39bed06)


academia forense digital

certificação chfi
