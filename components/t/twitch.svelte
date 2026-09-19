<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fitvqf1iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":432};
const content = `<path class="fitvqf1iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:twitch" {...props}></Icon>
