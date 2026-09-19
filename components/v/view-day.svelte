<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2qmt9b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="j2qmt9b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-day" {...props}></Icon>
