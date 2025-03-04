# Introduction

FletSpinkit1 for Flet.

## Examples

```
import flet as ft

from flet_spinkit1 import FletSpinkit1


def main(page: ft.Page):
    page.vertical_alignment = ft.MainAxisAlignment.CENTER
    page.horizontal_alignment = ft.CrossAxisAlignment.CENTER

    page.add(

                ft.Container(height=150, width=300, alignment = ft.alignment.center, bgcolor=ft.Colors.PURPLE_200, content=FletSpinkit1(
                    tooltip="My new FletSpinkit1 Control tooltip",
                    value = "My new FletSpinkit1 Flet Control", 
                ),),

    )


ft.app(main)
```

## Classes

[FletSpinkit1](FletSpinkit1.md)


