<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfqxavbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wfqxavbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:volume-mute" {...props}></Icon>
