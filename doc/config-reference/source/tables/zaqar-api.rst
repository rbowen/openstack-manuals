..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _zaqar-api:

.. list-table:: Description of API configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - **[DEFAULT]**
     -
   * - ``admin_mode`` = ``False``
     - (Boolean) Activate privileged endpoints.
   * - ``unreliable`` = ``False``
     - (Boolean) Disable all reliability constraints.
   * - **[notification]**
     -
   * - ``max_notifier_workers`` = ``10``
     - (Integer) The max amount of the notification workers.
   * - ``require_confirmation`` = ``False``
     - (Boolean) Whether the http/https/email subscription need to be confirmed before notification.
   * - ``smtp_command`` = ``/usr/sbin/sendmail -t -oi``
     - (String) The command of smtp to send email. The format is "command_name arg1 arg2".
   * - **[signed_url]**
     -
   * - ``secret_key`` = ``None``
     - (String) Secret key used to encrypt pre-signed URLs.
