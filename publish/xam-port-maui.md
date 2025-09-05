

[[xaml-xamlToMaui-kbase]]
## Imports

```csharp
using Xamarin.Essentials;
using Xamarin.Forms;

// Changed to:
using Microsoft.Maui.Essentials;
using Microsoft.Maui.Controls;
```

1.  **Updated C# Using Statements**

    *   Changed `using Xamarin.Forms;` → `using Microsoft.Maui.Controls;`
    *   Changed `using Xamarin.Essentials;` → `using Microsoft.Maui.Essentials;`
    *   Changed `using Xamarin.Forms.Xaml;` → `using Microsoft.Maui.Controls.Xaml;`
    *   Updated `Device.BeginInvokeOnMainThread` → `MainThread.BeginInvokeOnMainThread`

    **Original (Xamarin):**
    ```csharp
    using Xamarin.Essentials;
    using Xamarin.Forms;
    using Xamarin.Forms.Xaml;
    ```

    **New (MAUI):**
    ```csharp
    using Microsoft.Maui.Essentials;
    using Microsoft.Maui.Controls;
    using Microsoft.Maui.Controls.Xaml;
    ```

---

# Folder Copy All

*   `asset` --> `raw`
*   `drawable` --> `images`
*   Other folder files: 1 to 1

---

# Files

## Xam
*(No specific files listed for Xamarin in the original input)*

## Maui
*   `App.xaml`
*   `*` (Implies all other files, needs clarification if specific files are intended)

# prj specefic 

* CERS 
