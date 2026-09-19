<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvxufqi_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fvxufqi_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sunrise-over-mountains" {...props}></Icon>
