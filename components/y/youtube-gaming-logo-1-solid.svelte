<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07pqrkez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r07pqrkez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-gaming-logo-1-solid" {...props}></Icon>
