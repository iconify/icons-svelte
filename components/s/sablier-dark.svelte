<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htd18rb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htd18rb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sablier-dark" {...props}></Icon>
