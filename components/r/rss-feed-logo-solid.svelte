<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y19neniso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y19neniso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:rss-feed-logo-solid" {...props}></Icon>
