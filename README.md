# Main.sh
#
This script will prepare the VM by installing essential utilities 
- zip
- unzip
- stress

then will install 
- Node Exporter (for Prometheus), 
- load generation scripts (load_stress & log_generator) 
- install Alloy to push the logs

# load_stress 
will do a gentele System stress by creating light CPU, memory, and disk load for Prometheus

# log_generator
will generate logs for alloy/loki testing