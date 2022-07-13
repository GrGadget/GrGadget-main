project('GrGadget','cpp','c',
        default_options : ['cpp_std=c++17',
        'warning_level=3',
        'optimization=3'],
        version: '0.1')

liblatfield_proj = subproject('LATfield2')
liblatfield_dep  = liblatfield_proj.get_variable('liblatfield_dep')

libgevolution_proj = subproject('gevolution-1.2')
libgevolution_dep  = libgevolution_proj.get_variable('libgevolution_dep')

gadget4_proj = subproject('Gadget4')

grgadget = gadget4_proj.get_variable('gadget_exec')
