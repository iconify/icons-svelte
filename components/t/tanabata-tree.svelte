<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpxba793f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tpxba793f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:tanabata-tree" {...props}></Icon>
