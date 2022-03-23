# RL-Product-card

este es un paquete de pruebas de despliegue en NPM

### Leonel Rivas

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from "rl-product-card
```

```
<ProductCard
        product={product}
        className="bg-dark text-white"
        initialValues={{
          count: 6,
          maxCount: 10,
        }}
      >
        {({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>

```
