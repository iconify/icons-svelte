<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igp4owblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="igp4owblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:swimming-area" {...props}></Icon>
