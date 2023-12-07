## 我的世界基岩版（MCBE）块组件列表
完整的`BlockComponentsList`列表，description由Microsoft Copilot提供翻译
原链接：https://learn.microsoft.com/en-us/minecraft/creator/reference/content/blockreference/examples/blockcomponents/blockcomponentslist?view=minecraft-bedrock-stable

| 名称 | 默认值 | 类型 | 描述 |
| --- | --- | --- | --- |
| minecraft:breathability | solid | String | 决定方块是否可呼吸，即方块是被视为固体还是空气。需要实验性切换：Holiday Creator Features。 |
| minecraft:collision_box | true | Boolean/JSON Object | 定义与实体碰撞的方块区域。如果设置为true，则使用默认值。如果设置为false，则禁用与实体的碰撞。如果省略此组件，则使用默认值。需要实验性切换：Holiday Creator Features（在1.19.50之前的格式版本中）。 |
| minecraft:crafting_table | not set | JSON Object | 使你的方块成为一个自定义的工作台，启用工作台UI并能够制作配方。需要实验性切换：Holiday Creator Features（在1.19.50之前的格式版本中）。 |
| minecraft:destructible_by_explosion | true | Boolean/JSON Object | 描述方块的爆炸破坏性质。如果设置为true，则方块将具有默认的爆炸抗性。如果设置为false，则该方块不会被爆炸破坏。如果省略此组件，则方块将具有默认的爆炸抗性。 |
| minecraft:destructible_by_mining | true | Boolean / JSON Object | 描述方块的采矿破坏性质。如果设置为true，则方块将按默认时间被摧毁。如果设置为false，则该方块不会被采矿破坏。如果省略此组件，则方块将按默认时间被摧毁。 |
| minecraft:display_name | not set | Localization string | 指定当你在库存和快捷栏中悬停在方块上时显示的文本的语言文件键。如果给定的字符串无法解析为loc字符串，则将显示给定的原始字符串。如果省略此组件，则将使用方块的名称作为显示名称。需要实验性切换：Holiday Creator Features（在1.19.60之前的格式版本中）。 |
| minecraft:flammable | false | Boolean/JSON Object | 描述方块的可燃性质。如果设置为true，则使用默认值。如果设置为false，或者如果省略此组件，则方块将不会自然地从邻居那里着火，但仍然可以直接点燃。 |
| minecraft:friction | 0.4 | Decimal | 描述方块的摩擦力，范围为(0.0-0.9)。摩擦力影响实体在方块上移动的速度。值越大，摩擦力越大。 |
| minecraft:geometry | not set | Identifier string | 使用渲染此方块的几何文件的描述标识符。此标识符必须与当前加载的任何资源包中的现有几何标识符匹配。需要实验性切换：Holiday Creator Features（在1.19.40之前的格式版本中）。 |
| minecraft:light_dampening | 15 | Integer | 方块减少通过其传递的光线的量，范围为（0-15）。数值越高，光线减少得越多。 |
| minecraft:light_emission | 15 | Integer | 该方块将发出的光线量，范围为（0-15）。数值越高，发出的光线越多。 |
| minecraft:loot | not set | Path string | 指向行为包中的战利品表的路径。 |
| minecraft:map_color | not set | String | 设置方块在地图上渲染时的颜色。颜色以十六进制值的形式表示，格式为“#RRGGBB”。也可以表示为从0到255的[R, G, B]数组。如果省略此组件，方块将不会在地图上显示。 |
| minecraft:material_instances | not set | JSON Object | 方块的材质实例。将几何文件中的面或material_instance名称映射到实际的材质实例。您可以将材质实例对象分配给以下任何面：“up”, “down”, “north”, “south”, “east”, “west”, 或 “*”。您也可以给实例起一个您选择的名称，如“my_instance”，然后通过执行“north”:“my_instance”将其分配给一个面。需要实验性切换：Holiday Creator Features（在1.19.40之前的格式版本中）。 |
| minecraft:placement_filter | not set | JSON Object | 设置方块可以放置或存活的条件规则。需要实验性切换：Holiday Creator Features（在1.19.60之前的格式版本中）。 |
| minecraft:selection_box | true | Boolean / JSON Object | 定义玩家光标选择的方块区域。如果设置为true，则使用默认值。如果设置为false，玩家的光标将无法选择此方块。如果省略此组件，则使用默认值。需要实验性切换：Holiday Creator Features（在1.19.60之前的格式版本中）。 |
| minecraft:transformation | rotation[0, 0, 0] | Vector [a, b, c] | 方块围绕立方体中心的旋转，以度为单位。旋转顺序为[x, y, z]。角度需要是90的倍数。需要实验性切换：Holiday Creator Features（在1.19.80之前的格式版本中）。 |
| minecraft:unit_cube | not set | JSON Object | 指定使用单位立方体进行细分。 |