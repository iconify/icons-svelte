<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi5j-sb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mi5j-sb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sensor" {...props}></Icon>
