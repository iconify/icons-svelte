<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz3o49b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wz3o49b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:thumbs-up" {...props}></Icon>
