<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q125_acrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q125_acrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tennessee" {...props}></Icon>
