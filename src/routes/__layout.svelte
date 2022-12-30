<script>
    import "../app.css";
    import { loadTodos } from "../stores/todoStore.js";
	import { supabase } from "../supabase";
    console.log(supabase);

    
</script>

<div class="container mx-auto my-6 max-w-lg">        
    <slot></slot>
</div>