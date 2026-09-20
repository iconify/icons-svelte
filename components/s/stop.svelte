<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyyobbctf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jyyobbctf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stop" {...props}></Icon>
