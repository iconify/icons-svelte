<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydesnmqdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydesnmqdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:translate" {...props}></Icon>
