<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw4fu-bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hw4fu-bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:show-grid" {...props}></Icon>
