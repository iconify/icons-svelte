<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvz_3cbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kvz_3cbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:target-light" {...props}></Icon>
