# SLIX

A microkernel operating system targeting aarch64 (and eventually x86_64 and
TRISC). Originally developed inside the
[trisc](https://github.com/edadma/trisc) repository alongside the Sysl
language and TRISC ISA; the OS-specific code is being migrated here as it
matures.

## Layout

- `musl/` — ported musl libc (git subtree from upstream musl)

More to come as the OS code migrates out of trisc.
