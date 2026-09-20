<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7r-9rbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j7r-9rbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-left-outline" {...props}></Icon>
