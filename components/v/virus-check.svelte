<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm-1nv75i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm-1nv75i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:virus-check" {...props}></Icon>
