<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz8w-qbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fz8w-qbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:white-question-mark" {...props}></Icon>
