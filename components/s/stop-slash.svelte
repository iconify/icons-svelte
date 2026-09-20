<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy5nm_b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zy5nm_b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:stop-slash" {...props}></Icon>
