<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wahdl2leb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wahdl2leb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verifywise-light" {...props}></Icon>
