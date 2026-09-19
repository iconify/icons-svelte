<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8yv7tbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s8yv7tbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:web-publish" {...props}></Icon>
