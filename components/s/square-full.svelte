<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfggz2bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfggz2bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:square-full" {...props}></Icon>
