<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0j16dz6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0j16dz6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stop-line" {...props}></Icon>
