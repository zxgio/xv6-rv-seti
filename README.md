# xv6 per SETI @ UniGE

TLDR:

```
git clone https://github.com/zxgio/xv6-rv-seti.git
sudo docker run --name xv6 -ti --rm -v $(pwd)/xv6-rv-seti:/home/rv-docker/xv6 zxgio/xv6-riscv-tools
cd xv6
make qemu
```

Durante l'esecuzione `ctrl+P`, catturato dalla console di xv6, mostra la lista dei processi.
Invece, `ctrl+A`, seguito da:
- `c`, (dis)attiva la console di QEMU. Dalla console potete uscire dall'emulazione con `q` o, per esempio, vedere la tabella delle pagine con `info mem`.
- `x`, termina QEmu. Poi, per uscire dalla bash/docker, `ctrl-D` (come sempre).
