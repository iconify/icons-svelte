<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba3pwnull.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ba3pwnull"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:strava" {...props}></Icon>
