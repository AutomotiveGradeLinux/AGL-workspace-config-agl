### Invocation:

Clone workspace_automation


git clone https://github.com/meta-flutter/workspace-automation.git

cd workspace-automation

./flutter_workspace.py --remote https://gerrit.automotivelinux.org/gerrit/AGL/workspace-config-agl --enable agl-ivi-demo-flutter-qemu-master

Option:
replace
--enable agl-ivi-demo-flutter-qemu-master
with
--enable agl-ivi-demo-flutter-qemu-<branch_name>
e.g.
--enable agl-ivi-demo-flutter-qemu-unagi

