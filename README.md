# openstack
data pengerjaan openstack

ubah file os-env.yml sesuai dengan kebutuhan
untuk cara membuat openstack menggunakan template dan environtmen yaitu dengan perintah
" openstack stack create -t mystack-XX.yml -o os-env.yml "

apabila ingin menggunakan file templatenya saja tanpa menggunakan file environment
pindah kan semua data dari os-env.yml atau mengisi manual di mystack-XX.yml

tambahkan setiap parameters menggunakan
"default: "

untuk cara membuat openstack menggunakan template yaitu dengan perintah
" openstack stack create -t mystack-XX.yml "

openstack stack list

openstack server list

openstack server show heat-instance-XX

ssh cirros@10.20.XX.XXX

==== ketika sudah memasuki instancenya

$ hostname

heat-hostname-XX

$ exit

logout

==== ketika sudah keluar dari instancenya

<kolla-env> resqyhedy@podXX-controller:..
