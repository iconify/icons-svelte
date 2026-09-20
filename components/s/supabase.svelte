<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggcnueb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggcnueb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:supabase" {...props}></Icon>
