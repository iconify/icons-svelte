<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq0_znbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oq0_znbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:truenas-core-dark" {...props}></Icon>
