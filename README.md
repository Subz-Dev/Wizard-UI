# Wizard-UI
## [Warning] This Script was not Made by me!

### Loadstring
```
local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()
```

### Window
```
local PhantomForcesWindow = Library:NewWindow("Title")
```
### Tab
```
local KillingCheats = PhantomForcesWindow:NewSection("Tab")
```
### Button
```
KillingCheats:CreateButton("Button", function()
-- Script Here
end)
```
### Textbox
```
KillingCheats:CreateTextbox("TextBox", function(text)
-- Script Here
end)
```
### Toggle
```
KillingCheats:CreateToggle("Auto Ez", function(value)
-- Script Here
end)
```
### Dropdown
```
KillingCheats:CreateDropdown("DropDown", {"Hello", "World", "Hello World"}, 2, function(text)
-- Script Here
end)
```
### Slider
```
KillingCheats:CreateSlider("Slider", 0, 100, 15, false, function(value)
-- Script Here
 end)
```
### Picker
```
KillingCheats:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)
-- Script Here
end)
```

