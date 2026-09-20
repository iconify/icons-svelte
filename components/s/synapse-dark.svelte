<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wset72fas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wset72fas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synapse-dark" {...props}></Icon>
