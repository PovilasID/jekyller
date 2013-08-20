---

layout: default

style: |

    .caption img{
        width: 10em;
    }
    #Cover h2 {
        margin:90px 0 0;
        color: transparent;
        text-align:center;
        font-size:70px;

        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        color:#3C3D40;
        font-style:italic;
        font-size:35px;
        }
    #Cover div h2 img {
        position: inherit;
        width: 7em;
        height: 2em;
        z-index: 1;
    }
    #Contacts div h2 img {
        position: inherit;
        width: 7em;
        height: 2em;
        z-index: 1;
    }
    #Cover p img{
        width: 1024px;
        height: 640px;
    }
        #Cover p a {
            color:#3C3D40;
            }
        #Cover p.note {
            color: #999;
            margin-top: 190px;
            font-size:22px;
        }
        #Cover p.note a{
            color: #999;
        }
    .cover img {
        width: 1024px;
        height: 640px;
    }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
    #reklamos-srautas-akina h2{
        color: #FFF; 
    }
    #informacijos-filtras h2{
        color: #FFF; 
    }
---

# ![](pictures/logo_white.svg) {#Cover}
*Mobili aplikacija renginių atradimui*

{:.note}
Twitter: [@SocialheatApp](http://twitter.com/SocialheatApp) WWW: [Socialheat.lt](http://socialheat.lt)

![](pictures/bg0.png)

## Reklamos srautas akina
{:.cover .shout}
![](pictures/tunnel.jpg)

## Informacijos filtras
{:.cover }
![](pictures/glases.png)



## Kas atiminėja mums givybes

1. …Mes patys per protingi...
2. …Berlynas ir Kaunas skiriasi... 
3. …Keistas noras susipažinti su gamta.

## Naujas gyvenimo būdas

1. …Kalbėjimas su nepažystamais žmonėmis
2. …Berlyne ir Kaune tiek pat čeburiekinių
3. …Miškuose galima pagauti internetą... jei esi pakakmai aukštoj pušy

## Krištolinio rutulio transliacija

1. Šio mėnesio gale mokamos beta launchas (1$)
2. Suartys dėl srauto tiekimo bent su trimis kompanijomis
3. Išskirtinės teisės į keletos tarptautinių renginių publikavimą

<script type="text/javascript" src="https://www.google.com/jsapi?autoload={'modules':[{'name':'visualization',
       'version':'1','packages':['timeline']}]}"></script>
<script type="text/javascript">

google.setOnLoadCallback(drawChart);
function drawChart() {
  var container = document.getElementById('example2.2');
  var chart = new google.visualization.Timeline(container);
  var dataTable = new google.visualization.DataTable();
  dataTable.addColumn({ type: 'string', id: 'Term' });
  dataTable.addColumn({ type: 'string', id: 'Name' });
  dataTable.addColumn({ type: 'date', id: 'Start' });
  dataTable.addColumn({ type: 'date', id: 'End' });
  dataTable.addRows([
    [ '1', 'Programavimas', new Date(2013, 6, 10), new Date(2013, 8, 31) ],
    [ '2', 'Testavimas',        new Date(2013, 7, 10),  new Date(2013, 9, 15) ],
    [ '3', 'Testų pritaikymas',        new Date(2013, 8, 10),  new Date(2013, 9, 15) ],
    [ '4', 'Platinimas',  new Date(2013, 9, 15),  new Date(2013, 9, 31) ]]);

  var options = {
    timeline: { showRowLabels: false }
  };

  chart.draw(dataTable, options);
}
</script>

<div id="example2.2" style="width: 700px; height: 250px;"></div>

##Komanda

* Povilas
* Mantas
* Darius
* Tautvydas

## ![](pictures/Logo.svg) {#Contacts}
 info@socialheat.lt

 +370 623 56 228
 
 http://socialheat.lt