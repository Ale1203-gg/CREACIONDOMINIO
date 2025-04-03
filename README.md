# CREACION DOMINIO

## **Cómo Registrar y Configurar un Dominio en Hostinger**  

### **1. Registro y Compra de un Dominio**  
1. **Acceder a Hostinger:**  
   - Ingresa a [www.hostinger.com](https://www.hostinger.com).  
   - Crea una cuenta con tu correo electrónico o inicia sesión si ya tienes una.  

2. **Buscar y Comprar un Dominio:**  
   - Usa el buscador de dominios para encontrar un nombre disponible.  
   - Se recomienda elegir la opción más económica.  
   - Agrega el dominio al carrito y procede con el pago.  

3. **Finalizar la Compra:**  
   - Completa el pago con el método que prefieras.  
   - Espera a que el pago sea procesado y reflejado en tu cuenta.  

---

### **2. Configurar la IP Pública en el Dominio**  
1. **Acceder a la Configuración del Dominio:**  
   - Inicia sesión en **Hostinger**.  
   - Ve al menú principal y selecciona **Dominios**.  
   - Encuentra el dominio que compraste y haz clic en **Administrar**.  

2. **Modificar los Registros DNS:**  
   - Ve al menú de **DNS**.  
   - **Elimina todos los registros existentes** para evitar conflictos.  
   - Agrega dos nuevos registros tipo **A** con los siguientes valores:  
     - **Host:** @ → **IP Pública de tu VPS**  
     - **Host:** www → **IP Pública de tu VPS**  

3. **Guardar los cambios:**  
   - Confirma la configuración y guarda los registros.  
   - La propagación DNS puede tardar hasta 24 horas.  

---

### **Conclusión**  
Siguiendo estos pasos, tendrás tu dominio comprado y correctamente vinculado a tu IP pública. Ahora puedes usarlo en tu servidor con Hestia, PHP, Oracle Cloud o cualquier otro servicio que desees configurar. 
