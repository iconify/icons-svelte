<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3tun8sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs3tun8sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vimeo-logo-solid" {...props}></Icon>
