<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrsiusmyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xrsiusmyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-left" {...props}></Icon>
