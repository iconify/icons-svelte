<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ras2v3bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ras2v3bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voxmedia-coral-dark" {...props}></Icon>
