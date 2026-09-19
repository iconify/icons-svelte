<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2do9dblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2do9dblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:star-half" {...props}></Icon>
