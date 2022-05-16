# FPO_Multilayer_Server
FPO Multilayer Server

On the Windows server side, multilayer low-level technology (TCP-IP, winsockets) ensures very fast asynchronous frontend-backend communication running completely independently without the need for a running IIS server. The frontend applications connect exclusively to the first layer only, other server layers (databases, mailing, etc.) are directly for the frontend applications inaccessible and invisible. In the event of a failure of one of the first layer servers, the applications are automatically immediately switched to another functioning first layer server. First layer servers also function as mirrored file repositories which are immediately dated throughout the network according to the neural network principle.

The attached screenshot shows the three running layers of the server system at the same time, in this case only for illustration, all without problems on the same machine.

(c) 2022 Michal Krejci - michal.krejci@fpodevelopment.cz
