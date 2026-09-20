<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wju9krbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wju9krbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:sharing" {...props}></Icon>
