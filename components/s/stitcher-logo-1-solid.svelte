<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfkp55bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfkp55bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stitcher-logo-1-solid" {...props}></Icon>
