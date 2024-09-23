# Usage 🚀

To use PieRakNet in your project, follow these general steps:

1. **Import PieRakNet:** Import the relevant classes and functions from PieRakNet into your project.
2. **Initialize PieRakNet:** Set up PieRakNet in your application, configure connection settings, and handle incoming and outgoing messages.
3. **Handle Events:** Implement event handlers to manage various network events, such as incoming messages, connection status changes, etc.



Example of use:

```
from pieraknet.server import Server as PieRakNet

class BedrockServer:
    def main(self):
        from piebedrock.interface import GameInterface
        server = BedrockServer()
        interface = GameInterface()
        server = RakNetServer()
        server.logger.setLevel("INFO")
        server.game="MCPE"
        server.name="H"
        server.modt="G"
        server.interface = interface

        server.start()

if __name__ == '__main__':
    server = BedrockServer()
    server.main()
```



