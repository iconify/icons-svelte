<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzerpnb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dzerpnb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:winter-mahjong" {...props}></Icon>
