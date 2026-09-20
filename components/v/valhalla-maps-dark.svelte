<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/texztqb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="texztqb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:valhalla-maps-dark" {...props}></Icon>
