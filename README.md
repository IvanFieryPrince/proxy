# proxy
[filter "lfs"]
	clean = git lfs clean %f
	smudge = git lfs smudge %f
	required = true
[user]
	name = Ivan D Q Balendra
	email = bdqivan@gmail.com
[http]
    proxy = http://dmse:dmse2011@192.168.222.1:3128
[https]
    proxy = https://dmse:dmse2011@192.168.222.1:3128
