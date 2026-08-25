# **COMMAND LINE INTERFACE**

## **ENTER CLI MODES**

**User EXEC Mode**

```text
Router>
```

**Enter Privileged EXEC Mode**

```text
Router> enable
Router#
```

**Enter Global Configuration Mode**

```text
Router# configure terminal
Router(config)#
```

---

# **Universal Cisco CLI Configuration Steps**

## **Step 1: Enter Privileged EXEC Mode**

```text
enable
```

## **Step 2: Enter Global Configuration Mode**

```text
configure terminal
```

## **Step 3: Select the Interface**

```text
interface <interface-name>
```

**Example:**

```text
interface gigabitEthernet 0/0
```

## **Step 4: Configure the IP Address**

```text
ip address <ip-address> <subnet-mask>
```

**Example:**

```text
ip address 192.168.1.1 255.255.255.0
```

## **Step 5: Enable the Interface**

```text
no shutdown
```

## **Step 6: Exit Interface Configuration Mode**

```text
exit
```

## **Step 7: Verify Interface Configuration**

```text
show ip interface brief
```
