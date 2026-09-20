<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-vmqnfjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-vmqnfjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temu-dark" {...props}></Icon>
