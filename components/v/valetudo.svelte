<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-eaap4bd.css';
import '../../css/f/f86310bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-eaap4bd"/><path class="f86310bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:valetudo" {...props}></Icon>
