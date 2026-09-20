<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt8dwrb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yt8dwrb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon-and-tag" {...props}></Icon>
