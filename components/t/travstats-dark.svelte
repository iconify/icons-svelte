<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvnr3uzos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvnr3uzos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:travstats-dark" {...props}></Icon>
