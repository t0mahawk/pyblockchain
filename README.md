pyblockchain
============

python library for using the blockchain.info wallet api - https://blockchain.info/api




def CreateDepositeAddress:

https://blockchain.info/api/api_receive


	
class Wallet:

https://blockchain.info/api/blockchain_wallet_api


	def __init__(self, guid = '', password1 = '', password2 = ''):
	def Save(self, file = expanduser('~/wallet.dat')):
	def Load(self,file = expanduser('~/wallet.dat')):
	def Call(self, method, data = {}):
	def GetBalance(self):
	def GetAddressBalance(self,addr = '', confirmed = 0):
	def GetAddresses(self):
	def NewAddress(self, label = ''):
	def SendPayment(self, toaddr, amount , fromaddr = '', shared = 0, fee = 0.0000, note = ''):
	def SendManyPayment(self, txs = {} , fromaddr = '', shared = 0, fee = 0.0000, note = ''):



Donations: 1pbcic79jyAdAiisp5crN5C1iJmRq4aCM
