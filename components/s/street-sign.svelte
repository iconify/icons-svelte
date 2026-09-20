<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3l1bc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rn3l1bc2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:street-sign" {...props}></Icon>
