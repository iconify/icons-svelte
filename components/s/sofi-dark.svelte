<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1nyiyxfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d1nyiyxfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sofi-dark" {...props}></Icon>
