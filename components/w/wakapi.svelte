<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-gq_fbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-gq_fbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wakapi" {...props}></Icon>
