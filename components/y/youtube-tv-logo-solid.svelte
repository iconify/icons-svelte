<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3u7gvlxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3u7gvlxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-tv-logo-solid" {...props}></Icon>
