Paginators
==========

Paginators examples


//Example of use

  		$paginator = Factorycontroller::getClass(  'SharedPaginatorsJumpingController', false, view, $this->cache );
		$paginator->setTotalItems( $count_films[0]['count_films'] );
		$paginator->setItemsPerPage( ITEMS_PER_PAGE );
		$paginator->setCurrentPage( $this->current_page );
		$paginator_html = $paginator->build();
		
//NOTA: Hay que setear la URL Base de los botones del paginador
