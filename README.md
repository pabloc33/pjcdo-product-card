# PJCDO-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Pablo Contino

## Ejemplo

```
import {
  ProductButtons,
  ProductCard,
  ProductImage,
  ProductTitle,
} from "pjcdo-product-card";

```

```
 <ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
      >
        {({ reset, increaseBy, count, maxCount, isMaxCountReached }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>

```
