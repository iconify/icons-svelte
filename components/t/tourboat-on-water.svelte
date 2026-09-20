<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcby5t82t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hcby5t82t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tourboat-on-water" {...props}></Icon>
