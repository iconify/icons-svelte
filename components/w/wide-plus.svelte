<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7fbeus2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t7fbeus2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-plus" {...props}></Icon>
