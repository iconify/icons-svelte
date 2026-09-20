<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfxgklb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lfxgklb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spyder" {...props}></Icon>
