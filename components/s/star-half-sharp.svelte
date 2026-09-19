<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxydvgb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxydvgb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:star-half-sharp" {...props}></Icon>
