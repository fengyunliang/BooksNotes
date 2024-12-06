---

---

# 《CAN总线轻松入门与实践》

##  010

### Chapter 1: Overview and protocol specifications of CAN bus

#### 	_The architecture of computer networks refers to the collection of hierarchical structure model and protocols for each layer, that is, the functional definition and abstraction of the computer network and its components._

#### 	_Open System Interconnection Reference Model_

<img src="https://cdn.nlark.com/yuque/0/2022/png/32406541/1660008144249-ddd79e47-5d3f-499e-9a71-3b0d3ba0b151.png?x-oss-process=image%2Fformat%2Cwebp" alt="image.png" style="zoom:50%;" />

#### 	_Common physical interface standards include RS232, RS422, RS485, etc._

#### 	_The following devices are typically required to interconnect the network:_

##### 				RP repeater: <u>Used to connect physical layer segments</u>

##### 		Bridge: <u>Achieve the interconnection of different network at  data link layer</u>

##### 				Router: <u>Achieve the interconnection between multiple networks at network layer</u>

##### 		Gateway: <u>An inter-network protocol converter that can interconnect networks with different protocols</u>

#### 		_Network topology: The method and form of the interconnection between the sites in the network, common computer network topologies: Star topology, Bus topology, Ring topology, Tree topology, Mesh topology._

#### 	_CAN(Controller Area Network) belongs to the category of field bus, a serial communication bus with high performance, high reliability, easy development, low cost._

#### 	_CAN bus transform medium:_

##### 		Using dielectric materials: <u>high level is recessive state, low level is dominant state</u>

##### 		Using optical medium: <u>dark is recessive state, bright is dominant state</u> </u>

#### 	_Following four different frame types are used to represent and control in message transmission: data frames, remote frames, error frames, overload frames_

#### 	_data frame form:_

####  ![image.png](https://cdn.nlark.com/yuque/0/2022/png/32406541/1660008144479-33ba8559-ba15-48dc-9e96-51a3158f02ed.png?x-oss-process=image%2Fformat%2Cwebp%2Fresize%2Cw_825%2Climit_0)

#### 	_Coding-bit padding: whenever, sender detect_