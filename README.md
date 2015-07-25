# proxy
# Add these lines in your .gitconfig file in your %USERFILES%

[filter "lfs"]
	clean = git lfs clean %f
	smudge = git lfs smudge %f
	required = true
[http]
    proxy = http://dmse:dmse2011@192.168.222.1:3128
[https]
    proxy = https://dmse:dmse2011@192.168.222.1:3128
