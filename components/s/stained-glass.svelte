<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxcicy_ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fxcicy_ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stained-glass" {...props}></Icon>
