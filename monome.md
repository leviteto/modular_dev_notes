# monome stuff.

## making your own Teletype ii cables

Bought Teletype, found ii cable with only one-to-one connector. So I need to look for ways to daisy-chain my monome devices to be controlled simultaneously with Teletype.

### cable spec
 * 6pins (2x3)
 * 0.1" x 0.1" spacing 
 * max daisy chain count: 4 
   * need to use ii busboard v2 w/ external power to drive more than 4.

### pin header spec
  * 3 pins (1x3)
  * 0.1" (2.54mm) spacing.
  
### options:
 * make your own cascaded cable
   * connector 2.54mm pitch (
     * https://www.sparkfun.com/products/10651
       * schematics: https://cdn.sparkfun.com/datasheets/Cables/HookUp/Morethanall%20Female%20IDC%20Connector%20F-C2-xx.pdf
   * header which can be used as a coupler
     * https://cdn.sparkfun.com/datasheets/Cables/HookUp/Morethanall%20Female%20IDC%20Connector%20F-C2-xx.pdf
   * another connector 
     * Amphenol T812 Series 2.54mm Pitch Cable Mount IDC Connector, Socket, 6 Way, 2 Row
       * http://uk.rs-online.com/web/p/idc-connectors/8323613/
   * 1.27mm pitch 6-way flat ribbon cable (this is 16way, need to be splitted into 6 ways)
     * http://uk.rs-online.com/web/p/flat-ribbon-cable/2899874/
  
 * pre-made 6pin IDC cable
  * from mouser
     * http://www.mouser.jp/ProductDetail/Adafruit/371/?qs=sGAEpiMZZMsMyYRRhGMFNm%252b9ZebcIWMbBYdVRmD%252bLGw=
   * directly from adafruit
     * https://www.adafruit.com/product/371
  
 * ii busboards
  * https://llllllll.co/t/ii-bus-board/4911
    * on sale, but paying shipment only for this doesn't make that much sense...
      * https://llllllll.co/t/ii-bus-board/4911/24
 * ii bus board v2
   * https://llllllll.co/t/ii-bus-board-v2-with-pullups/6777/9
    
### references
   * ll-bus board
     * https://llllllll.co/t/ii-bus-board/4911/9
