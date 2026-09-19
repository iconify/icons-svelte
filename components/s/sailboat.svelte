<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0dtz2lio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="x0dtz2lio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sailboat" {...props}></Icon>
