<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_8tzebwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o_8tzebwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:transit-vehicle-with-destination-display-on-railway-track-in-tunnel" {...props}></Icon>
