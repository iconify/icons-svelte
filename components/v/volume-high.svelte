<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfwj7h0yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mfwj7h0yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:volume-high" {...props}></Icon>
