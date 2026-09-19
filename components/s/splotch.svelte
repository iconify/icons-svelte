<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi4exwl-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oi4exwl-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:splotch" {...props}></Icon>
