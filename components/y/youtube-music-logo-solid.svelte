<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mky3ybctq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mky3ybctq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-music-logo-solid" {...props}></Icon>
