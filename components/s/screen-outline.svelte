<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkx1uwbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rkx1uwbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:screen-outline" {...props}></Icon>
