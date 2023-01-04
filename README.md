# FastNet2 - a Incredible and Powerful Networking Module
Next-gen of FastNet & Networking Module

# * FastNet2 - APIs

# FastNet2:IsExist(remoteName: string): boolean
-> Check if the remote is exists
# FastNet2:toBestFormNumber(num: number): number | string
# FastNet2:Get(remoteName: string, waitFor: number): any
-> Receive/Get remote, waitFor is yielded
# FastNet2:Create(remoteName: string, typeRemote: string): any
-> Create new remote, typeRemote: "Event"/"Events"

# * FastNet2 - Functions

# FastNet2Remote:Listen(waitTill: boolean | any, callback: any): never
-> Connect/Listen to the remote connection receiver
# FastNet2Remote:Disconenct(messageOutput: string): undefined
-> Disconenct currently connected remote, messageOutput print-out when disconnected
# FastNet2Remote:Destroy()
-> Destroy & Disconnect the remote
# FastNet2Remote:Disconnected()
-> Check if the Remote is disconencted
