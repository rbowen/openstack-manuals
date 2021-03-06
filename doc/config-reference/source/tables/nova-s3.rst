..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _nova-s3:

.. list-table:: Description of S3 configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - **[DEFAULT]**
     -
   * - ``image_decryption_dir`` = ``/tmp``
     - (String) DEPRECATED: Parent directory for tempdir used for image decryption EC2 API related options are not supported.
   * - ``s3_access_key`` = ``notchecked``
     - (String) DEPRECATED: Access key to use S3 server for images EC2 API related options are not supported.
   * - ``s3_affix_tenant`` = ``False``
     - (Boolean) DEPRECATED: Whether to affix the tenant id to the access key when downloading from S3 EC2 API related options are not supported.
   * - ``s3_host`` = ``$my_ip``
     - (String) DEPRECATED: Hostname or IP for OpenStack to use when accessing the S3 API EC2 API related options are not supported.
   * - ``s3_port`` = ``3333``
     - (Port number) DEPRECATED: Port used when accessing the S3 API. It should be in the range of 1 - 65535 EC2 API related options are not supported.
   * - ``s3_secret_key`` = ``notchecked``
     - (String) DEPRECATED: Secret key to use for S3 server for images EC2 API related options are not supported.
   * - ``s3_use_ssl`` = ``False``
     - (Boolean) DEPRECATED: Whether to use SSL when talking to S3 EC2 API related options are not supported.
