<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt8j62bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mt8j62bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:spiral" {...props}></Icon>
