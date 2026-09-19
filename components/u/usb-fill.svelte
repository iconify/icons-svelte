<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luft5hbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="luft5hbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:usb-fill" {...props}></Icon>
