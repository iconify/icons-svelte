<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcvh03bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hcvh03bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:woman-dancing" {...props}></Icon>
