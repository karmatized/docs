{% if currentVersion ver_gt "enterprise-server@2.21" %}

{% note %}

**Note:** Your site administrator must enable {{ site.data.variables.product.prodname_code_scanning }} for {{ site.data.variables.product.product_location_enterprise }} before you can use this feature. If you want to use {{ site.data.variables.product.prodname_actions }} to scan your code, the site administrator must also enable {{ site.data.variables.product.prodname_actions }} and set up the infrastructure required. For more information, see "[Configuring {{ site.data.variables.product.prodname_code_scanning }} for your appliance](/enterprise/admin/configuration/configuring-code-scanning-for-your-appliance)."

{% endnote %}

{% endif %}