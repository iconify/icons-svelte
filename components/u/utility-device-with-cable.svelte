<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgc11fb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pgc11fb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-device-with-cable" {...props}></Icon>
