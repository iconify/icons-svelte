<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikucneb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ikucneb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:wand-stars-inverse" {...props}></Icon>
