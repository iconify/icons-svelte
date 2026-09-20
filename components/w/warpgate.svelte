<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do5wwxbpa.css';
import '../../css/a/az6iwibpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="do5wwxbpa"/><path class="az6iwibpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:warpgate" {...props}></Icon>
