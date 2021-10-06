# RabbitMQ with Ansible

Start of a template for installing and configuring rabbitmq

## Parameters

 * `rabbitmq_version` - Version of RabbitMQ
 * `rabbitmq_download_url` - URL of tar.xz for release
 * `erlang_version` - Version of Erlang
 * `erlang_download_url` - URL of RPM for erlang

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```

## TODO

 * Separate Erlang install
 * Parameterize Erlang version
 * Enable Management Plugin
