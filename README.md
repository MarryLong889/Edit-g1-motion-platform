# Edit-g1-motion-platform

## Prepare

need to download unitree_sdk2 and unitree_mujoco repo first
Next is the detailed steps

### unitree_sdk2

#### Depency

```
sudo apt install cmake gcc build-essential libeigen3-dev
```

#### build

```
cd /opt
sudo mkdir unitree_robotics
cd ~/unitree_sdk2
mkdir build
cmake .. -DCMAKE_INSTALL_PREFIX=/opt/unitree_robotics
sudo make install  # wait for building 
```
### unitree_mujoco

refer to the unitreerobotics' guide

## Usage
