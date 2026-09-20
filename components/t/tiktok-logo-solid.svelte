<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhxrv3bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhxrv3bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tiktok-logo-solid" {...props}></Icon>
