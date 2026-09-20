<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sflztryon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sflztryon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sofe-light" {...props}></Icon>
