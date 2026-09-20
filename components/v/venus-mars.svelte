<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aueqyccur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aueqyccur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:venus-mars" {...props}></Icon>
