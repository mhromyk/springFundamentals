package com.pluralsight.service;

import com.pluralsight.repository.*;
import java.util.List;
import com.pluralsight.model.Customer;
import com.pluralsight.service.CustomerService;

public class CustomerServiceImpl implements CustomerService {
	
	CustomerRepository customerRepository = new HibernateCustomerRepositoryImpl();

	/* (non-Javadoc)
	 * @see com.pluralsight.service.CustomerService#findAll()
	 */
	@Override
	public List<Customer> findAll(){
		
		return customerRepository.findAll();
	}
}
