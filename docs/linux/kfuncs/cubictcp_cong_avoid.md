---
title: "KFunc 'cubictcp_cong_avoid' - eBPF Docs"
description: "This page documents the 'cubictcp_cong_avoid' eBPF kfunc, including its defintion, usage, program types that can use it, and examples."
---
# KFunc `cubictcp_cong_avoid`

<!-- [FEATURE_TAG](cubictcp_cong_avoid) -->
[:octicons-tag-24: v5.13](https://github.com/torvalds/linux/commit/e78aea8b2170be1b88c96a4d138422986a737336)
<!-- [/FEATURE_TAG] -->

Do new cwnd calculation

## Definition

<!-- [KFUNC_DEF] -->
`#!c void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked)`
<!-- [/KFUNC_DEF] -->

## Usage

!!! example "Docs could be improved"
    This part of the docs is incomplete, contributions are very welcome

### Program types

The following program types can make use of this kfunc:

<!-- [KFUNC_PROG_REF] -->
- [BPF_PROG_TYPE_STRUCT_OPS](../program-type/BPF_PROG_TYPE_STRUCT_OPS.md)
<!-- [/KFUNC_PROG_REF] -->

### Example

!!! example "Docs could be improved"
    This part of the docs is incomplete, contributions are very welcome
