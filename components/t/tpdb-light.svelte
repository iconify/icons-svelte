<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moj3q8fhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="moj3q8fhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tpdb-light" {...props}></Icon>
