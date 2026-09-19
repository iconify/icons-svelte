<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipfdksjuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ipfdksjuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:wink2" {...props}></Icon>
