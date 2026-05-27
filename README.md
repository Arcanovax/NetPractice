*This project has been created as part of the 42 curriculum by mthetcha.*


# NetPractice

## Description

NetPractice is a practical networking exercise. The goal is to configure a simulated networks, covering fundamental TCP/IP concepts such as IP addressing, masks, and default gateways.

There are a total of 10 levels, with the difficulty increasing exponentially. Each level presents a faulty diagram that you must repair by modifying the available fields until all the goals are achieves.


## Instructions



### Running

1. Download and unzip the project files from the projetc page.
2. Navigate to the folder and run the launch script:

```bash
./run.sh
```

*This will start a local web server and open the interface in your browser automatically.*


3. Then open your browser and go to: `http://localhost:49242`

### Usage

- Enter your **42 login** in the input field.
- Alternatively, use the **"evaluation"** tab to generate a random configuration.
- For each level, modify the fields until the network works correctly.
- Click `Check again` to verify your configuration.
- Once a level is validated, click `Get my config` to download your configuration file.
- Then click on `Next Level` to move on to the next level
- Repeat for all 10 levels.

### Submission requirements

To validate this project you have to achieve all the levels and download the 10 configuration files.

## Submission details

The 10 configuration files must be placed at the root of the repository


## Resources

### Networking Concepts Studied

- **TCP/IP addressing**: is used to assign a unique address to each device on a network so that they can communicate.
- **Subnet masks**: is used to determine which part of an IP address corresponds to the network and which part corresponds to the device.
- **Default gateway**: serves as an exit point for sending data to other networks, such as the Internet.
- **Routers and switches**: A router connects multiple networks to each other, while a switch connects multiple devices in the same network.
- **OSI layers**: are used to organize network communications into specific layers, in this project, we focus in particular on Layers 2 (Data Link) and 3 (Network).

### References

- [IP Address basics](https://en.wikipedia.org/wiki/IPv4)
- [Subnet basics](https://en.wikipedia.org/wiki/Subnet)
- **Peer to Peer**: learned mostly from peers


### AI Usage

- **README drafting** — generating a first version of this README, then reviewed and adapted manually.
