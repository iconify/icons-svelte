<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfw6i0twr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sfw6i0twr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sunset" {...props}></Icon>
