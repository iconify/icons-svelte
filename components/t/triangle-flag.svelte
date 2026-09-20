<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln3awga8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ln3awga8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-flag" {...props}></Icon>
