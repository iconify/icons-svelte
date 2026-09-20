<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixm8i3f1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ixm8i3f1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ship" {...props}></Icon>
