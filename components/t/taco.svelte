<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_4ct0mzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h_4ct0mzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:taco" {...props}></Icon>
