<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u624y-kis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u624y-kis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-gaming-logo-2-solid" {...props}></Icon>
