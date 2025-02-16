---
id: dxCalendar.Options.dateSerializationFormat
type: String
default: undefined
---
---
##### shortDescription
Specifies the date-time value serialization format. Use it only if you do not specify the [value](/api-reference/10%20UI%20Components/dxCalendar/1%20Configuration/value.md '/Documentation/ApiReference/UI_Components/dxCalendar/Configuration/#value') at design time.

---
Without a value, the UI component cannot detect its format. In this case, specify the **dateSerializationFormat** property that supports the following formats:

- `"yyyy-MM-dd"` - a local date  

- `"yyyy-MM-ddTHH:mm:ss"` - local date and time  

- `"yyyy-MM-ddTHH:mm:ssZ"` - the UTC date and time  

- `"yyyy-MM-ddTHH:mm:ssx"` - date and time with a timezone

This property applies only if the **forceIsoDateParsing** field is set to **true** in the [global configuration object](/api-reference/50%20Common/utils/config(config).md '/Documentation/ApiReference/Common/utils/#configconfig').

[note] If you are going to change the **value** using the API, make sure that it has the same format that you specified in this property.

#####See Also#####
- [Troubleshooting - Date values are parsed or serialized incorrectly](/concepts/70%20Data%20Binding/90%20Troubleshooting/Date%20values%20are%20parsed%20or%20serialized%20incorrectly.md '/Documentation/Guide/Data_Binding/Troubleshooting/#Date_values_are_parsed_or_serialized_incorrectly')