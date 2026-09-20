<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_xhkgbdq.css';
import '../../css/j/j--gjob4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":308};
const content = `<path class="s_xhkgbdq"/><path class="j--gjob4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:svelte" {...props}></Icon>
