# Crop Grow Event

To use this event use the following import:
```groovy:no-line-numbers
import net.minecraftforge.event.world.BlockEvent.CropGrowEvent
```

## Sub-Classes
This event extends the following events and can use all their methods and fields: <br>
[BlockEvent](index.md)

## Methods
# Crop Grow Event.Pre

To use this event use the following import:
```groovy:no-line-numbers
import net.minecraftforge.event.world.BlockEvent.CropGrowEvent.Pre
```

## Sub-Classes
This event extends the following events and can use all their methods and fields: <br>
[CropGrowEvent](index.md), [BlockEvent](index.md)

## Methods
```groovy:no-line-numbers
boolean hasResult()
```

# Crop Grow Event.Post

To use this event use the following import:
```groovy:no-line-numbers
import net.minecraftforge.event.world.BlockEvent.CropGrowEvent.Post
```

## Sub-Classes
This event extends the following events and can use all their methods and fields: <br>
[CropGrowEvent](index.md), [BlockEvent](index.md)

## Methods
```groovy:no-line-numbers
net.minecraft.block.state.IBlockState getOriginalState()
```
