

[[xam-port-maui]]
remove all stacklayout with grid

## Maui app have xaml xml files having controls like :
## **Controls (UI Elements)**

- **`Image`** - Displays pictures/graphics
- **`Label`** - Shows text content
- **`Button`** - Interactive clickable element
## & 
## **Containers (Layout Elements)**

- **`ContentPage`** - Root page container
- **`ScrollView`** - Enables scrolling for overflow content
- **`VerticalStackLayout`** - Arranges children vertically

# Purpose and Behaviour of Containers 

[[det_8973]]

# Key points  Mwcb= minworkcodeblock

```xml
<ContentPage xmlns="http://schemas.microsoft.com/dotnet/2021/maui"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             x:Class="CERS.MainPage">
</ContentPage>
```
- **`<ContentPage>`**: Root container representing a single page/screen
- **`xmlns="...maui"`**: Default namespace for MAUI controls (Image, Label, Button)
- **`xmlns:x="...xaml"`**: XAML namespace for XAML-specific features (x:Name, x:Class)
- **`x:Class="CERS.MainPage"`**: Links this XAML to the MainPage.xaml.cs code-behind class



## **Additional Common Controls & Containers**

### **More Controls:**

- `Entry` - Text input field
- `Picker` - Dropdown selection
- `Switch` - Toggle on/off
- `Slider` - Range selector
- `DatePicker` - Date selection

### **More Containers:**

- `HorizontalStackLayout` - Arranges children horizontally
- `Grid` - Flexible rows/columns layout
- `StackLayout` - General stacking (vertical/horizontal)
- `Frame` - Container with border/shadow
- `Border` - Decorative container with styling

## **Pattern:**


```xml

<Container>  
    <Control Property="Value" />  
    <AnotherContainer>  
        <Control />  
    </AnotherContainer>  
</Container>
```

Your understanding is spot-on - MAUI uses this hierarchical structure where **containers** hold and arrange **controls** to build the UI layout.