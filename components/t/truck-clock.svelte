<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmhhk40sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmhhk40sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:truck-clock" {...props}></Icon>
