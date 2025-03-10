# F0RT1ND-Chat-TTM
This app and server uses the TTMP2 protocol (Talk to Mii Protocol 2)

# How to set up?
Make sure you edited this value in vs and module1.vb:
Dim listener As New TcpListener(IPAddress.Any, 8888)

in form1.vb in the app sln:
Client = New TcpClient("127.0.0.1", 8888)

replace these values with ur own
