<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi2p-lb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pi2p-lb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wheelchair" {...props}></Icon>
