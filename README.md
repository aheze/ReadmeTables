# ReadmeTables
Tables don't need to be boring

## Plain Markdown Table

Vegetables | Fruits | Grains
:--- | :---: | ---:
Potatos | Apples | Oats
Corn | Oranges | Rice
Broccoli | Bananas | Wheat
Lettuce | Peaches | Barley

## Plain Markdown Table with Styling

Vegetables | Fruits | Grains
:--- | :---: | ---:
*Potatos* | **Apples** | ~Oats~
**_Corn_** | Oranges | **~Rice~**
`Broccoli` | [Bananas](https://google.com) | **_`Wheat`_**
**`Lettuce`** | [`Peaches`](https://google.com) | [**`Barley`**](https://google.com)

## Plain Markdown Table with Code?

UIKit | SwiftUI
--- | ---
```Swift
class ViewController: UIViewController {
    @IBAction func buttonPressed(_ sender: Any) {
       	print("Button pressed!")
    }
}
``` | ```Swift
struct ContentView: View {
    var body: some View {
        Button("Press me") {
        	print("Button pressed!")
        }
    }
}
```

## HTML Table with Code

<table>
	<tr>
    	<th>
        	UIKit
        </th>
        <th>
        	SwiftUI
        </th>
    </tr>
	<tr>
<td>
        
```Swift
class ViewController: UIViewController {
    @IBAction func buttonPressed(_ sender: Any) {
       	print("Button pressed!")
    }
}
```

</td>
<td>
       
```Swift
struct ContentView: View {
    var body: some View {
        Button("Button pressed!") {
        	print("Button pressed!")
        }
    }
}
```
</td>
</tr>
</table>

## Plain Markdown Table with Images

Vegetables | Fruits | Grains
:--- | :---: | ---:
Potatos ![](/Images/potato.jpg) | Apples ![](/Images/apple.jpg)  | Oats ![](/Images/oat.jpg) 
Corn ![](/Images/corn.jpg)  | Oranges ![](/Images/orange.jpg)  | Rice ![](/Images/rice.jpg) 
Broccoli ![](/Images/broccoli.jpg)  | Bananas ![](/Images/banana.jpg)  | Wheat ![](/Images/wheat.jpg) 
Lettuce ![](/Images/lettuce.jpg)  | Peaches ![](/Images/peach.jpg)  | Barley ![](/Images/barley.jpg) 
