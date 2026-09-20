<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nglok4ztb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nglok4ztb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:video-subtitles-solid" {...props}></Icon>
