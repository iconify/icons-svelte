<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m61w3obew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m61w3obew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sportarr" {...props}></Icon>
