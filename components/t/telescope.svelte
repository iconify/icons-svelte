<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf4x2lbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mf4x2lbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:telescope" {...props}></Icon>
