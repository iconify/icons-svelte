<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0l6vme3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q0l6vme3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:woman-climbing" {...props}></Icon>
