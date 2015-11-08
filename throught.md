red green

myId OtherId

myElement otherElement

---------------------------

initial all undefined

---------------------------

Establish Connection
get myId

---------------------------

if get call first, callee >> green + getElement'green' >> myElement, (local)getElement'red' >> otherElement

else if make call first, caller >> red + getElement'red' >> myElement, (local)getElement'green' >> otherElement

---------------------------

send message with peerId

if get otherId, otherElement.drawPosition(x,y)



