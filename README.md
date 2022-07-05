# Practicas

/// esto va en el controlador

@RestController
@CrossOrigin(origins = "*")
@RequestMapping("/api/")
public class UsuarioController {
	
	@Autowired
	private UsuarioService usuarioServices;
	
	//Listar Usuarios
	@GetMapping("listar")  // listar puede ser cualquier nombre en este caso es un get
	public List<Usuario> getUsuarios(){
		return null;
	}
