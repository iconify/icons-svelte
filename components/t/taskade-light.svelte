<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rivcu-b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rivcu-b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taskade-light" {...props}></Icon>
