```
add_filter('edd_owp_paddle_generate_pay_link', function ($payload, $purchase_data) {
    if ($purchase_data['downloads'][0]['id'] == '13826') {
        $payload['product_id'] = 573878;
        unset($payload['title']);
        unset($payload['webhook_url']);
        unset($payload['prices']);
    }

    return $payload;
}, 10, 2);
```
