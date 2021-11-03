import os,time
def modul():
	try:
		import AminoLab
		print("checking module")
		time.sleep(2)
		ver=AminoLab.__version__
		if ver !='1.6':
			print("ur module has old version")
			time.sleep(2)
			os.system("pip install AminoLab==1.6")
			print("module updated")
	except:
		print("module doesnt install")
		time.sleep(2)
		os.system("pip install AminoLab==1.6")
		print("module installed")
modul()
import AminoLab
print("right module")
os.system("clear")
print("writed on AminoLab 1000-7 by @xaquake")
client = AminoLab.Client()
email = input("email: ")
password = input("password: ")
try:
	client.auth(email=email,password=password)
	print("successful login")
except:
	print("incorrect login")
msgtype = "109"
clients = client.my_communities()
for x, name in enumerate(clients.name, 1):
 print(f"{x}.{name}")
ndc_Id = clients.ndc_Id[int(input("choose community: "))-1]
chats = client.my_chat_threads(ndc_Id=ndc_Id, size=100)
for z, title in enumerate(chats.title, 1):
 print(f'{z}.{title}')
thread_Id = chats.thread_Id[int(input("choose chat: "))-1]
def ghoul():
	a=1007-7
	while a > -1:
		msg=(f"{a} - 7 = {a-7}")
		client.send_message(ndc_Id, thread_Id, msg, msgtype)
		a-=7	
		print(f"message {a} sended")
		time.sleep(1)
ghoul()
msg="Я - гуль"
client.send_message(ndc_Id,thread_Id,msg,msgtype)
print("You - ghoul")
