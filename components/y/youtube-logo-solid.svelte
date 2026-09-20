<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkw-3rbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkw-3rbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-logo-solid" {...props}></Icon>
