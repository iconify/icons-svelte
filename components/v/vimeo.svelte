<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neo39kk3j.css';
import '../../css/e/e5z8i_kna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="neo39kk3j"/><path class="e5z8i_kna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vimeo" {...props}></Icon>
