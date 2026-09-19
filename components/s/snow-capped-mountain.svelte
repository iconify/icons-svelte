<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkuu9-b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tkuu9-b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:snow-capped-mountain" {...props}></Icon>
