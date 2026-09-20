<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o14i3uhye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="o14i3uhye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:windmill-11" {...props}></Icon>
