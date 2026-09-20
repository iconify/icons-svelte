<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuu2htbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuu2htbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-mute" {...props}></Icon>
