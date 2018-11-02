---
layout: method
title: transition
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  static OMR::Om::ObjectMap * transition(OMR::Om::Context &, Handle<OMR::Om::Object>, Infra::Span<const SlotAttr>):
    arguments:
      - description: __OPTIONAL__
        name: cx
        type: OMR::Om::Context &
      - description: __OPTIONAL__
        name: object
        type: Handle<OMR::Om::Object>
      - description: __OPTIONAL__
        name: slots
        type: Infra::Span<const SlotAttr>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: static OMR::Om::ObjectMap * transition(OMR::Om::Context & cx, Handle<OMR::Om::Object> object, Infra::Span<const SlotAttr> slots)
  static OMR::Om::ObjectMap * transition(OMR::Om::Context &, Handle<OMR::Om::Object>, Infra::Span<const SlotAttr>, std::size_t):
    arguments:
      - description: __OPTIONAL__
        name: cx
        type: OMR::Om::Context &
      - description: __OPTIONAL__
        name: object
        type: Handle<OMR::Om::Object>
      - description: __OPTIONAL__
        name: slots
        type: Infra::Span<const SlotAttr>
      - description: __OPTIONAL__
        name: hash
        type: std::size_t
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: static OMR::Om::ObjectMap * transition(OMR::Om::Context & cx, Handle<OMR::Om::Object> object, Infra::Span<const SlotAttr> slots, std::size_t hash)
  static OMR::Om::ObjectMap * transition(OMR::Om::Context &, Handle<OMR::Om::Object>, std::initializer_list<SlotAttr>):
    arguments:
      - description: __OPTIONAL__
        name: cx
        type: OMR::Om::Context &
      - description: __OPTIONAL__
        name: object
        type: Handle<OMR::Om::Object>
      - description: __OPTIONAL__
        name: slots
        type: std::initializer_list<SlotAttr>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: static OMR::Om::ObjectMap * transition(OMR::Om::Context & cx, Handle<OMR::Om::Object> object, std::initializer_list<SlotAttr> slots)
---
