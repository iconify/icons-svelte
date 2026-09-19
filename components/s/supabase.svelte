<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl1bm0zko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jl1bm0zko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:supabase" {...props}></Icon>
