<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r00akdbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r00akdbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:twitch-outlined" {...props}></Icon>
