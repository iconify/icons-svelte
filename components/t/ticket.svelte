<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-x0v-3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wk-x0v-3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ticket" {...props}></Icon>
