
# Eletric Meter <img src="ic_playstore.png" width="24">
Android application for Atorch BLE device

## How to use
1. Plug your USB Digital Tester into the charger and the Bluetooth indicator will light up.
2. Launch this app on your phone, and tap bluetooth icon on 'Searching'.
3. If cannot connect (timeout), please re-try and check the your test device's bluetooth icon.
 (If bluethooth icon does not blink but ligth up, pull the plug and plug in.)
 Still you cannot connect, please remove this app. Your deivce cannot support.
4. When you tab the device name or device address, you can see 'Settings'.

## ScreenShot
<table>
  <tr>
    <th>Searching</th>
    <th>View Screen</th>
    <th>Settings</th>
  </tr>
  <tr>
    <td><img src="https://github.com/zephy-lee/ElectricMeter/blob/main/searching_Electric_Meter.jpg" width="324" height="600"/></td>
    <td><img src="https://github.com/zephy-lee/ElectricMeter/blob/main/portrait_Electric_Meter.jpg" width="324" height="600"/></td>
    <td><img src="https://github.com/zephy-lee/ElectricMeter/blob/main/settings_Electric_Meter.png" width="324" height="600"/></td>
  </tr></table>
<img src="https://github.com/zephy-lee/ElectricMeter/blob/main/land_Electric_Meter.jpg" width="702" height="324"/>

## Download
<https://play.google.com/store/apps/details?id=com.zephy.vatester>

## Reference
- <https://github.com/NiceLabs/atorch-console>
- <https://github.com/msillano/UD18-protocol-and-node-red>

## Donation

If this app helps to you, please give me a cup of coffee :) <br>
<div id="paypal-button-container-P-46498706UP711203DNKI2QAA"></div>
<script src="https://www.paypal.com/sdk/js?client-id=BAAqnGY16c626SSQF5Zyw2GF56aD6Q90XZdtOYhWkPZTKX2veOT77zOk7aYyYrox2_WyXqz6FTckL1LTtc&vault=true&intent=subscription" data-sdk-integration-source="button-factory"></script>
<script>
  paypal.Buttons({
      style: {
          shape: 'rect',
          color: 'gold',
          layout: 'vertical',
          label: 'paypal'
      },
      createSubscription: function(data, actions) {
        return actions.subscription.create({
          /* Creates the subscription */
          plan_id: 'P-46498706UP711203DNKI2QAA'
        });
      },
      onApprove: function(data, actions) {
        alert(data.subscriptionID); // You can add optional success message for the subscriber here
      }
  }).render('#paypal-button-container-P-46498706UP711203DNKI2QAA'); // Renders the PayPal button
</script>
