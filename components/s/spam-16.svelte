<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk-vv_b6c.css';
import '../../css/d/d4i5-t89q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rk-vv_b6c"/><path clip-rule="evenodd" class="d4i5-t89q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:spam-16" {...props}></Icon>
