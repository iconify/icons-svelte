<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jusstw7zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jusstw7zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:stopwatch-fill" {...props}></Icon>
