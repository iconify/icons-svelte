<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w36xbxbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w36xbxbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-2-line" {...props}></Icon>
