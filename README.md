# Installation

    cd $ROUNDCUBE_HOME/plugins
    git clone https://github.com/nicolasb827/roundcube-dspam-plugin dspam

# Configuration

Ensure to load the plugins, and configure DSPAM URL:

## main.inc.php

    $rcmail_config['plugins'] = array('dspam', '..');
    
    You are strongly encouraged to use HTTPS !
    
    $rcmail_config['dspam_url_scheme'] = 'https://';
    $rcmail_config['dspam_url_host'] = 'mail.opencsi.com';
    $rcmail_config['dspam_url_path'] = '/dspam/';
    
