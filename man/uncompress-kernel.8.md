# UNCOMPRESS-KERNEL(8)

## NAME

uncompress-kernel - Uncompress kernel after installation

## SYNOPSIS

**uncompress-kernel**

## DESCRIPTION

Rockchip U-Boot does not support compressed kernel.
However, Linux by default will generated compressed kernel.
Thus this hook is required to boot with Rockchip U-Boot.
