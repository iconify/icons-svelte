<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9p70bb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9p70bb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:snapchat-logo-block" {...props}></Icon>
