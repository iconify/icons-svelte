<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnmdtxbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tnmdtxbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wavelog-light" {...props}></Icon>
