<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spg-nfber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spg-nfber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:screen-duplicate-filled" {...props}></Icon>
