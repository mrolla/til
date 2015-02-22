# Linux
A collection of common things that may

### Preventing sudo to remember your password
By preventing sudo to remember your password for a short amount of time, you will be always prompted when it is needed.

    sudo visudo

And lower the timeout:

    Defaults	timestamp_timeout = 0
