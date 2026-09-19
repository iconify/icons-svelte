<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td8hh25oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="td8hh25oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:thong-sandal" {...props}></Icon>
