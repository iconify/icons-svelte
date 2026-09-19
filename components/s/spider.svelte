<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5xl-o4hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x5xl-o4hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:spider" {...props}></Icon>
