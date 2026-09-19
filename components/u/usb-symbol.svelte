<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c--03vb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c--03vb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:usb-symbol" {...props}></Icon>
