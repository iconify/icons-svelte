<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucovixi8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ucovixi8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:womans-sandal" {...props}></Icon>
