<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f43icszpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f43icszpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wechat-pay-logo" {...props}></Icon>
