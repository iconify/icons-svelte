<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt73z4b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mt73z4b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:window" {...props}></Icon>
