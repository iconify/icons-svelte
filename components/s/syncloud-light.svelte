<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrgg1kb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrgg1kb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:syncloud-light" {...props}></Icon>
