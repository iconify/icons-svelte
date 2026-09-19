<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlzab3bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlzab3bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wc" {...props}></Icon>
