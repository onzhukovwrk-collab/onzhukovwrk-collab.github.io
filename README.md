# onzhukovwrk-collab.github.io
test
<script type="text/javascript" src="//cdn.pushwoosh.com/webpush/v3/pushwoosh-web-notifications.js" async></script>
<script type="text/javascript">
var Pushwoosh = Pushwoosh || [];
Pushwoosh.push(['init', {
    logLevel: 'info', // possible values: error, info, debug
    applicationCode: '9A5E2-629F0', // you application code from Pushwoosh Control Panel
    apiToken: 'qNJYl6Qj66EG8E7x4L2mRKSA7AQLhjMWtr0rDXduarwMjx9c5qk56rD1Dv6SiGej3bYIOkw5g9mr2q1Bqi1r', //  Device API Token
    defaultNotificationTitle: 'Pushwoosh', // sets a default title for push notifications
    defaultNotificationImage: 'https://yoursite.com/img/logo-medium.png', // URL to custom custom notification image
    autoSubscribe: false, // or true. If true, prompts a user to subscribe for pushes upon SDK initialization
subscribeWidget: {
    enable: true,
    position: 'topRight', //possible values: ‘bottomLeft’, ‘bottomRight’, ‘topLeft’, ‘topRight’
    bgColor: '#12AE7E',
    bellColor: 'black',
    bellStrokeColor: '#08754f',
    bellButtonBorder: '1px solid #379676',
    shadow: '0px 0px 6px rgba(0, 0, 0, 0.75)',
    size: '48px',
    indent: '20px',
    zIndex: '999999',
    tooltipText: {
      successSubscribe: 'You are successfully subscribed!',
      needSubscribe: 'Get notifications about important news!',
      blockSubscribe: 'Click to see how to get notifications',
      alreadySubscribed: 'You are already subscribed'
    },
    userId: 'user_id', // optional, set custom user ID
    tags: {
        'Name': 'John Smith'     // optional, set custom Tags
    }
}]);
</script>
