# 🐞 SauceDemo Bug Reports

## 🐛 BUG-SD-001: Product Not Appearing in Cart

- **Environment**: Chrome 125.0  
- **Steps**:
  1. Login as `standard_user`
  2. Click "Add to cart"
  3. Click on cart icon  
- **Expected**: Product listed in cart  
- **Actual**: Cart is empty  
- **Severity**: High  
- **Status**: Open

---

## 🐛 BUG-SD-002: Checkout Allows Empty ZIP Code

- **Environment**: Firefox 126.0  
- **Steps**:
  1. Add product to cart
  2. Begin checkout
  3. Leave ZIP field empty and continue  
- **Expected**: Error message required  
- **Actual**: Proceeded to next step  
- **Severity**: Medium  
