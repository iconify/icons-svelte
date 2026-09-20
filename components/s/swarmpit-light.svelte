<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1-96opxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c1-96opxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swarmpit-light" {...props}></Icon>
