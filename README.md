# Nextjs Medusajs Commerce

## Requirements

- lando v3.20.8
- node v18
- yarn v1.22.19

## Lando

```
lando start
```

## Commerce backend - Medusajs

```
cd commerce;
yarn install;
yarn seed; // Import configuration
yarn dev;
```

Medusa admin url: http://localhost:7001

Admin credentials:  
user: admin@medusa-test.com  
pass: supersecret

## Commerce storefront - Nextjs

```
cd commerce-storefront;
yarn install;
yarn dev;
```

Storefront url: http://localhost:8000  
See demo store products: http://localhost:8000/store
