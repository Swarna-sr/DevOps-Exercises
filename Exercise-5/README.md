# Exercise 5: Docker Security with AppArmor

## Security Concepts Covered
1. **Unconfined Execution**: Executed container with --security-opt apparmor=unconfined.
2. **Defense in Depth**: Evaluated AppArmor security policy enforcement under --cap-add SYS_ADMIN.
3. **Custom Profiles**: Formatted custom AppArmor security profile restricting /tmp write access and package management binaries.
