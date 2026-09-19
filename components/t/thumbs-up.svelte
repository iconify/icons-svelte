<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv0hl_r7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vv0hl_r7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:thumbs-up" {...props}></Icon>
