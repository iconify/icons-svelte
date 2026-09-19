<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnj22268l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fnj22268l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:scarf" {...props}></Icon>
