<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgy1x0b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgy1x0b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:x" {...props}></Icon>
