<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnabqxbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hnabqxbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spliit-light" {...props}></Icon>
