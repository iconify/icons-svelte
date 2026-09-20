<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0qkxxb-q.css';
import '../../css/u/u0bzg8byf.css';
import '../../css/v/v4-7eu8rv.css';
import '../../css/z/ztmfb6bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="u0qkxxb-q"/><circle class="u0bzg8byf"/><path class="v4-7eu8rv"/><path class="ztmfb6bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:speechless" {...props}></Icon>
