# TGS Rules & Details

[GOTO RULES](https://github.com/IxGamerXL/TGS-Rules/blob/main/README.md#rules)

[GOTO CURRENCY](https://github.com/IxGamerXL/TGS-Rules/blob/main/README.md#currency)

[GOTO CODE](https://github.com/IxGamerXL/TGS-Rules/blob/main/README.md#code)

## RULES

### #1: No Binary Bytes
Binary is considered unoptimized as they take six more characters than Hexidecimal, so we are not allowing the use of "Bytes" when it comes to purchases in our clan.

Binary: `0b00000000` - `0b11111111`
Hexidecimal: `0x00` - `0xFF`

The only cost to this is that The Shards clan isn't compatible with Hexidecimals, but this will allow us to have more compact credits and use less space.

### #2: Don't Reject Your Code
In other words: **Do not take action where it could be dangerous unless authorized.** We must stay to code, especially in attack plans or advanced teamwork-mandatory procedures.

### #3: Respect One Another
Be decent, remain respectful, and pay attention to supervisors. We may all be differently programmed, but we should all respect each other.

### end

## CURRENCY
Our currency is referred as Hexidecimals or H$ for short. H$ is either referred by a simple number, or by `0x--`. Hexidecimal values can be increased in length by adding more digits to them (e.g: `0xff` -> `0x01ff`).

Hexidecimals can contain >16 million times the amount that one Binary byte can store using `0xffffffff`, making this the preferred currency for any purchases in TGS.

You can refer a value of H$ by using Hexidecimal or plain numbers (if you can't translate).


## CODE
```lua
ClanData = {
    memberCount = 2, -- (U: March 30th 2022)
    clanOwner = nil,
    creationDate = "March 30th 2022"
}

Currency = {
    name = {"H$", "Hexidecimals"},
    full = "0xHEX"
}
```
