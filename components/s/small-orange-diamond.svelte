<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0gu42b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a0gu42b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:small-orange-diamond" {...props}></Icon>
