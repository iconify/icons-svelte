<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phuh8mbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="phuh8mbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:saxophone" {...props}></Icon>
