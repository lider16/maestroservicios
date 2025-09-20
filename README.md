# Maestro

Una aplicación Flutter completa con autenticación de usuarios integrada con Supabase.

## ✨ Características

- **Autenticación completa**: Login, registro y recuperación de contraseña
- **Integración con Supabase**: Backend as a Service para autenticación
- **UI moderna**: Interfaz de usuario limpia y responsiva
- **Buenas prácticas**: Código siguiendo las mejores prácticas de Flutter
- **Análisis estático**: Sin warnings o errores de linting
- **Multiplataforma**: Compatible con Android, iOS, Web, Windows, Mac y Linux

## 🚀 Inicio rápido

### Prerrequisitos

- Flutter SDK (versión 3.9.2 o superior)
- Una cuenta en [Supabase](https://supabase.com)

### Configuración

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/lider16/maestroservicios.git
   cd flutter_auth_app
   ```

2. **Instala las dependencias**:
   ```bash
   flutter pub get
   ```

3. **Configura Supabase**:
   - Crea un proyecto en Supabase
   - Copia tu URL del proyecto y API key
   - Actualiza `lib/constants.dart` con tus credenciales

4. **Ejecuta la aplicación**:
   ```bash
   flutter run
   ```

## 📱 Pantallas

### Login
- Inicio de sesión con email y contraseña
- Navegación a registro y recuperación de contraseña

### Registro
- Creación de nueva cuenta de usuario
- Validación de contraseñas
- Confirmación por email (configurable en Supabase)

### Recuperación de contraseña
- Envío de enlace de recuperación por email
- Navegación de vuelta al login

### Home
- Página de bienvenida con mensaje motivacional
- Accesible solo después de autenticación

## 🛠️ Desarrollo

### Análisis de código
```bash
flutter analyze
```

### Formateo
```bash
dart format lib/
```

### Pruebas
```bash
flutter test
```

## 📋 Configuración de Supabase

1. Ve a tu proyecto en Supabase
2. Ve a Authentication > Settings
3. Configura:
   - **Site URL**: Tu dominio (para desarrollo: `http://localhost:3000`)
   - **Redirect URLs**: Agrega las URLs permitidas
   - **Enable email confirmations**: Según tus necesidades

## 🤝 Contribución

1. Fork el proyecto
2. Crea tu rama de feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🆘 Soporte

Si tienes problemas:
1. Revisa la documentación de [Supabase](https://supabase.com/docs)
2. Consulta la documentación de [Flutter](https://flutter.dev/docs)
3. Abre un issue en este repositorio

---

¡Feliz coding! 🚀
