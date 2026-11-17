<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkccombky.css';
import '../../css/r/r0yz7hbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="gkccombky"/><path class="r0yz7hbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:torsher" {...props}></Icon>
