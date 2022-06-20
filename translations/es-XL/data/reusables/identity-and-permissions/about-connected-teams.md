Una vez que los equipos {% data variables.product.prodname_dotcom %} están conectados a un grupo IdP, tu adiministrador IdP debe realizar cambios en la membrecía de equipo a través del proveedor de identidad. Si se conecta a un equipo con un grupo de IdP, no puedes administrar la membrecía de equipo en {% data variables.product.product_name %} o utilizando la API.

Para administrar el acceso a un repositorio para cualquier equipo de {% data variables.product.prodname_dotcom %}, incluyendo los equipos conectados a un grupo de IdP, debes hacer cambios en {% data variables.product.product_name %}. Para obtener más información, consulta "[Acerca de equipos](/articles/about-teams)" y "[Administrar el acceso de equipo a un repositorio de la organización](/articles/managing-team-access-to-an-organization-repository)."

Puedes seleccionar los repositorios a los cuales quieres que los miembros del equipo tengan acceso predeterminadamente. Los grupos conectados por IdP tendrán acceso a estos repositorios automáticamente. Para obtener más información, consulta la sección "[Administrar el acceso de un equipo a un repositorio organizacional](/articles/managing-team-access-to-an-organization-repository)".

Todos los cambios a la membrecía de equipo que se hagan con tu IdP aparecerán en la bitácora de auditoría en {% data variables.product.product_name %} como cambios que realiza el bot de sincronización de equipos. Tu IdP enviará datos de la membresía de equipo a {% data variables.product.prodname_dotcom %} una vez por hora.