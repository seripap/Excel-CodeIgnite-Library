Excel CodeIgnite Library
=========
###Modified by Daniel Seripap <daniel@seripap.com>
=========
Originally by Leenix (http://lenix.co.uk), modified for CodeIgnite by Daniel Seripap. 

###USAGE:
			$this->load->library('Excel');
			$this->Excel->set_file_name('Filename.xls');
			$this->Excel->addHeader('Name');
			$this->Excel->addHeader('Sex');
			$this->Excel->addRow('Daniel');
			$this->Excel->addRow('Male');
			$this->Excel->sendFile();