<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nax3mvb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nax3mvb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tube-wave-left-wave-right" {...props}></Icon>
