<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve1v3g8oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ve1v3g8oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:straight-ruler" {...props}></Icon>
