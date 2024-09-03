# My-new-product-card

Este es un paquete de pruebas de despliegue en NPM.

### Fernanda Nuñez

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'do-product-card'
```

```
    <ProductCard
      product={product}
      initialValues={{
        count: 4
      }}
       >
      {({reset, count, maxCountReached, increaseBy}) => (
        <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
        </>
      )}
    </ProductCard>
```