# JSON
 - **JavaScript Object Notation (JSON)** : is a data-interchange format. JSON can represent numbers, booleans, strings, null, arrays (ordered sequences of values), and objects (string-value mappings) made up of these values. JSON does not natively represent more complex data types like functions, regular expressions, dates, and so on.(Date objects by default serialize to a string containing the date in ISO format, so the information isn't completely lost.) If you need JSON to represent additional data types, transform values as they are serialized or before they are deserialized.
  
```json 
   {
    "one": 2,
    "three": {
        "point_1": "point_2",
        "point_3": 3.4
    },
    "list": [
        "one",
        "two",
        "three"
    ]
}
```
> serialized: Publish or broadcast (a story or play) in regular installments.

## Serialization

- **serialization:**
  In the context of computing and data, serialization means converting an object or data structure into a format suitable for storage (like a file) or transmission (like over a network), often into a stream of bytes. The reverse process, converting that stream back into the original object, is called deserialization. 

- **Purpose:**
Serialization allows you to save the state of an object or data structure so it can be preserved or sent to another system, and then later recreated. 

- **How it works:**
Serialization transforms complex data structures into a simpler, linear format (like a sequence of bytes) that can be easily stored or transmitted. 


# How to calculate internet speed

**Speed is usually measured in megabits per second (Mbps), where:**
- 1 byte = 8 bits
- 1 Kbps = 1,000 bits per second
- 1 Mbps = 1 million bits per second

**Manual Calculation:**

If you want to calculate it manually, follow these steps:

1. Download a File: Start downloading a file from a reliable source.
2. Measure Time: Use a stopwatch to measure how long it takes to download the file.
3. Calculate Speed:
```
- Use the formula: Speed (Mbps) = ( File Size (MB) × 8 / Download Time (seconds))
- For example, if you downloaded a 100 MB file in 20 seconds: Speed = (100 × 8 / 20 ) = 40 Mbps
```

1. Factors Affecting Speed:

- **Network Congestion:** More users can slow down the speed.
- **Distance from Router:** The farther you are, the weaker the signal.
- **Wired vs. Wireless:** Wired connections (Ethernet) are usually faster than wireless.
- **ISP Throttling:** Your Internet Service Provider (ISP) may limit your speed based on your plan.


### Normally, we calculate internet speed by dividing it by 8.


      So if you have 1 Mbps, your actual download speed will be 1 * 1000 / 8 = 125 KBps.

      Be aware of the b, small b = bit , big B = Byte.


### Download speeds in browsers or torrents show speeds in MBps (Megabytes per second).


     So, if your ISP provides 30 Mbps, your actual max download speed will be:

     30 * 1000 / 8 = 3.75 MBps.

> Internet providers advertise speeds in Mbps (Megabits per second).


# Calculate percentage

     amount = percentage you want to calculate * total value / 100

 **Calculate gram to amount**
        
     gram = (total gram / total value) * amount

 > (total gram / total value) it will provide value per gram, then multiply amount to get exact gram for provided amount.

 