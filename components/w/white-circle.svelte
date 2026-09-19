<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drkpzc5wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="drkpzc5wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:white-circle" {...props}></Icon>
