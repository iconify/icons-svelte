<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol9yrdunc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ol9yrdunc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:valhalla-maps-light" {...props}></Icon>
