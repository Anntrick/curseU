# Contenedores

Los contenedores son los elementos que recibirán en su interior los controles de nuestra aplicación. Por defecto, la aplicación se iniciará con un único contenedor, de tipo Grid, que conoremos más adelante. Si lo eliminas, no podrás hacer más que añadir un único control en tu aplicación.

Necesitarás un contenedor principal, pudiendo este contener otros contenedores en su interior. También puedes cambiarlo a cualquiera de tu preferencia, hasta conseguir la interfaz gráfica que desees.

## Stackpanel

El StackPanel es un contenedor que apila de forma automática los controles que se colocan en su interior. Por defecto, lo hace en horizontal, pero esto puede ser cambiado.

Un StackPanel que está vacío:

```xaml
<StackPanel></StackPanel>
```

Un StackPanel que apila dos botones en su interior:

```xaml
<StackPanel>
    <Button Content="Un boton" Margin="5"/>
    <Button Content="Otro boton" Margin="5"/>
</StackPanel>
```

Un StackPanel que apila dos botones en horizontal:

```xaml
<StackPanel Orientation="Horizontal">
    <Button Content="Un boton" Margin="5"/>
    <Button Content="Otro boton" Margin="5"/>
</StackPanel>
```

## Grid

## Dockpanel