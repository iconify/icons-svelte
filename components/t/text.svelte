<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-wusac0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-wusac0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:text" {...props}></Icon>
