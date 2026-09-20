<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn14cjvwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="yn14cjvwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-41" {...props}></Icon>
