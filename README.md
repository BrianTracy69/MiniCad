# MiniCad

MiniCad is a library for C#/WPF. It includes basic controls and a custom control for drawing simple shape objects. You can pull it and experience.

## Controls

1. DrawingControl
2. MiniButton
3. MiniTextBox
4. MiniPasswordBox
5. MiniComboBox
6. MiniRadioButton
7. MiniCheckBox
8. MiniSwitch
9. MiniDatePicker
10. MiniSlider
11. MiniModal

## Photo

![image](https://raw.githubusercontent.com/BrianTracy69/MiniCad/refs/heads/main/MiniCad.PNG)

## Installation

To install MiniCad, you can use NuGet Package Manager:

```sh
Install-Package MiniCad
```

## Usage

Here’s a simple example of how to use MiniCad in your project:

```cs
<Window ...
        xmlns:mini="clr-namespace:MiniCad.Controls;assembly=MiniCad">
    <Grid>
        <StackPanel>
            <mini:DrawingControl Height="200"/>
            <mini:MiniButton Content="Button"/>
        </StackPanel>
    </Grid>
</Window>
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or feedback, please open an issue on GitHub.
