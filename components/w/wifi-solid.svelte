<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q78h75nsj.css';
import '../../css/w/wlug79bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q78h75nsj"/><path class="wlug79bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:wifi-solid" {...props}></Icon>
