<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_hqlra2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_hqlra2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:writing-hand" {...props}></Icon>
