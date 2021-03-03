# information_schema.applicable_roles

SELECT 
USER,
HOST,
GRANTEE,
GRANTEE_HOST,
ROLE_NAME,
ROLE_HOST,
IS_GRANTABLE,
IS_DEFAULT,
IS_MANDATORY
FROM information_schema.applicable_roles;
