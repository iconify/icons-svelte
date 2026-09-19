<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjf09_bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yjf09_bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:trade-mark" {...props}></Icon>
