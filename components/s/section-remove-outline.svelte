<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg501v9yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eg501v9yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:section-remove-outline" {...props}></Icon>
