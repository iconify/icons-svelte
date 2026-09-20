<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7o009b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t7o009b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-button-computer-mouse-with-scroll-wheel" {...props}></Icon>
