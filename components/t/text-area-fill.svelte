<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p14dg1asc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p14dg1asc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-area-fill" {...props}></Icon>
