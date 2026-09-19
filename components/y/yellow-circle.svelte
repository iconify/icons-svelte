<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iakis3b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iakis3b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:yellow-circle" {...props}></Icon>
