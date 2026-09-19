<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6a-3ivxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m6a-3ivxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:yarn" {...props}></Icon>
