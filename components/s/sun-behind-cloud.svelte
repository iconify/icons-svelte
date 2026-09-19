<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6o9oubkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q6o9oubkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sun-behind-cloud" {...props}></Icon>
