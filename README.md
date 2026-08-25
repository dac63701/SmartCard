# Smart Card
A nRF54L15 based Bluetooth Tracker in a Credit Card sized package

![Smart Card PCBA](/review/SmartCard.png)

The goal of this project was to create a small and slim Bluetooth tracker that would fit into a credit card enclosure. To do this, a 0.8mm thin 80mah battery was used along with a 0.8mm PCB. The device makes use of wireless charging with a BQ51013B so that it is easy to use and keep charged. There is also a custom battery charger and protection circuit. It uses a BQ298009 for protection and a BQ25100 for charging. Finally there is a TPS62840 for sourcing 1v8 from the battery and the antenna along with a matching network.

## Components
Check the [bom](https://github.com/dac63701/SmartCard/blob/main/production/bom.csv) for more details on the PCB components.
Standard PLA was used for the Prototype case.
The battery is a 084545 battery from [Alibaba](https://www.alibaba.com/product-detail/GEB-ultra-0-8mm-Thickness-084545_1601492203632.html?spm=a2756.trade-list-buyer.0.0.5fea76e93Ynkdn).

## Case Files
Check [OnShape](https://cad.onshape.com/documents/73dd8871ae024b497bb44b73/w/69cf76015be0ecbff129bf07/e/5547e5b9bb5f69b8ddd4b47d?renderMode=0&uiState=6a8e2710a56b25790309a2e5) for the files.
