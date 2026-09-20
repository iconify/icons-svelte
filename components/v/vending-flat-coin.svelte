<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfvyi0osq.css';
import '../../css/u/uo31dmb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sfvyi0osq"/><path class="uo31dmb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-flat-coin" {...props}></Icon>
