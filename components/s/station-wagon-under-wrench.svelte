<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2rb7ob_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b2rb7ob_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon-under-wrench" {...props}></Icon>
