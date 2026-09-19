<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/addq5hbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="addq5hbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:small-blue-diamond" {...props}></Icon>
