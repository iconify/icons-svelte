<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad1o_lclx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ad1o_lclx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:small-blue-diamond" {...props}></Icon>
