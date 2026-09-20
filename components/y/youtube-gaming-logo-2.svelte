<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytv7pabhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytv7pabhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-gaming-logo-2" {...props}></Icon>
