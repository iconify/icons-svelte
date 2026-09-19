<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uik-t4bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uik-t4bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:underline-stroke-12" {...props}></Icon>
