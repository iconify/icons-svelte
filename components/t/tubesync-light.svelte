<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys8dllbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys8dllbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tubesync-light" {...props}></Icon>
