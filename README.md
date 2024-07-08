всвязи с последними событиями надо после разворачивания ВМ, зайти на каждую машину и прописать из под sudo другие репы
sed -i 's/mirrorlist/#mirrorlist/g' /etc/yum.repos.d/CentOS-*
sed -i 's|#baseurl=http://mirror.centos.org|baseurl=http://vault.centos.org|g' /etc/yum.repos.d/CentOS-*
 так же для выполнения первого задания нужно установить дополнительно 
yum install policycoreutils-python
выполнения задания можно посмотреть в скриншотах, они расположены по нумерации по очереди выполнения дз
