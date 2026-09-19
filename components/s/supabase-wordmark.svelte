<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxj0m6wlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pxj0m6wlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:supabase-wordmark" {...props}></Icon>
