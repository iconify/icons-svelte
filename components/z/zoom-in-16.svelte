<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwxfhhz9b.css';
import '../../css/p/pxcxtbcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mwxfhhz9b"/><path class="pxcxtbcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:zoom-in-16" {...props}></Icon>
