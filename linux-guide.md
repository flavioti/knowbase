# linux-guide

lsb_release -a - Show os info
uptime = Session info
uname -r = Kernel info
cat /etc/passwd = Lista dos usuários
cat /etc/shadow | grep -i flavio = Mostra senhas dos usuários
passwd = Mudar senha usuário
find / -iname teste = Pesquisa de arquivos
man xxxxxx  = Show manual about application
id <user> = Show information about user
gpasswd -a $USER docker
cat /etc/group | grep flavio
cat /etc/sudoers.d = Sudoers file
df -i -T / = mostrar quantidade de inodes
ulimit = Mostra configuração de quota de memória
ulimit -u = Limite de processos por sessão
ulimit -a = limite de memória por aplicação
ifconfig wlp1s0
nmcli d
route -en
netcat -l 5000
netcat -vz -w10 127.0.0.1 5000
tcpdump -i wlp1s0 dst uol.com.br
mtr pag.com.br
whois meupag.com.br
nslookup -q=NS meupag.com.br
nslookup -q=A meupag.com.br
nmap <ip> = Mostra portas abertas
dig +short meupag.com.br
telnet 127.0.0.1 5000
systemctl start <service.name>
netstat -ntpl | grep grafana
docker inspect <container-code>
gpg -c secret.txt
gpg secret.txt.gpg = Descriptografar
lsof -i = Conexões de entrada
free -h
echo > 1 /proc/sys/vm/drop = Limpar memória
