<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnjp8bb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnjp8bb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:supabase" {...props}></Icon>
