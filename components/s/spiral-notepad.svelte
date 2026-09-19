<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeedibbap.css';
import '../../css/q/qzrf2_c2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aeedibbap"/><path class="qzrf2_c2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:spiral-notepad" {...props}></Icon>
