# InputStyle class

表示表单的输入样式。

```csharp
public class InputStyle
```

## Public Members

| name | description |
| --- | --- |
| [InputStyle](sdk/InputStyle/InputStyle.md)() | The default constructor. |
| [DefaultValue](sdk/InputStyle/DefaultValue.md) { get; set; } | 表单输入的默认值。 |
| [DisplayName](sdk/InputStyle/DisplayName.md) { get; set; } | 表单输入的显示名称。 |
| [Height](sdk/InputStyle/Height.md) { get; set; } | 表单输入的显示高度。 |
| [HelpText](sdk/InputStyle/HelpText.md) { get; set; } | 表单输入的提示信息。 |
| [InputType](sdk/InputStyle/InputType.md) { get; set; } | 表单的输入类型。 |
| [IsRequired](sdk/InputStyle/IsRequired.md) { get; set; } | 表单输入是否必填项。 |
| [ListItems](sdk/InputStyle/ListItems.md) { get; set; } | 表单输入的列表项。 当表单的输入类型（InputType）为列表项（Checkbox、Radio、Select）时启用。 |
| [MaxNum](sdk/InputStyle/MaxNum.md) { get; set; } | 表单输入的最大字符数。 0 代表不限制。 |
| [MinNum](sdk/InputStyle/MinNum.md) { get; set; } | 表单输入的最小字符数。 0 代表不限制。 |
| [RegExp](sdk/InputStyle/RegExp.md) { get; set; } | 表单输入验证的正则表达式。 当表单输入的验证规则（ValidateType）为正则表达式验证（RegExp）时启用。 |
| [ValidateType](sdk/InputStyle/ValidateType.md) { get; set; } | 表单输入的验证规则。 |
| [Width](sdk/InputStyle/Width.md) { get; set; } | 表单输入的显示宽度。 |

## See Also

* namespace [SiteServer.Plugin](sdk/README.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->