# useForm

Ejemplo de uso:
``` javascript
    const initialForm = {
        nombre: 'José Morente',
        correo: 'josemorenteg98@gmail.com',
    }
    const { values, handleInputChange, reset } = useForm(initialForm);
```