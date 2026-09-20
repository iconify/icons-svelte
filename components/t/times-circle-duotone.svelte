<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vla37tbfm.css';
import '../../css/w/wgw8u43wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vla37tbfm"/><path class="wgw8u43wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-circle-duotone" {...props}></Icon>
