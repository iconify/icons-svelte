<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4qvfxzmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":466,"height":671};
const content = `<path class="r4qvfxzmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:u" {...props}></Icon>
