# README

## L'Atelier de Lucie

*Canevas, broderie, point de croix et tricot*

## Alias service internet archive

rm -rf remote_alias && ln -s '/Volumes/service internetArchives$/NEWSLETTERS/TRIGGER/RELANCE_PANIER/ATELIER_LUCIE' remote_alias

## Persona 

- fotolia ref : 122507797
- [ Suivre ce lien ]( https://fr.fotolia.com/Search/Model/122507797?offset=200 )

## Intégration

- type responsive

- Dimensions
  - desktop
    - \> 480w = direction display row on 636w && < 480w = display column on 320w
  - mobile
    - @media only screen and (max-width: 480px),(max-device-width: 1024px) and (orientation : portrait)

##  specific debug

*Orange*
- vertical alignment = valign="middle" + style="vertical-align: middle;"

*Outlook*
- font-face:: font-family =

```html
// hack OUTLOOK font-face/font-stack error rendering
  <!--[if mso]>
    <style type="text/css">
      body, table, td {font-family: Arial, Helvetica, sans-serif !important;}
    </style>
  <![endif]-->
```


## Color

<table>
  <tr>
    <td>Primary</td>
    <td>Secondary</td>
    <td>Tertiary</td>
  </tr>
  <tr>
    <td style="background-color: #C70082;" >&nbsp;</td>
    <td style="background-color: #71439A;" >&nbsp;</td>
    <td style="background-color: #FBB600;" >&nbsp;</td>
  </tr>
</table>

## main nav item ( 25/02/19 )

<table>
  <tr>
    <td style="text-align: center;">Broderie,<br />canevas </td>
    <td style="text-align: center;">Loisirs<br />Créatifs</td>
    <td style="text-align: center;">Tricot &<br />crochet</td>
    <td style="text-align: center;">Couture &<br />mercerie </td>
    <td style="text-align: center;">Arts<br />graphiques </td>
    <td style="text-align: center;">Puzzles</td>
  </tr>
</table>

```css
.nav {
  font-family: Georgia, 'Times New Roman', Times, serif;
}
```
