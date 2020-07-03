# wpcli-ql
A simple SQL like interface for WP-CLI

## Install

## Example
`wp query SELECT theme.name FROM themes WHERE theme.status='active' AND EXISTS (FROM Plugins where plugin.name ='woocommerce' AND status='active')" `
