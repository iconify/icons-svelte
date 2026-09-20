<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urrrm4wfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urrrm4wfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidal-light" {...props}></Icon>
