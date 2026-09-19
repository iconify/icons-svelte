<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccub-obgi.css';
import '../../css/z/zbv5-bbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ccub-obgi"/><path class="zbv5-bbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:tag" {...props}></Icon>
