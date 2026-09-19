<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7rrbjb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7rrbjb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:volume-mute2" {...props}></Icon>
