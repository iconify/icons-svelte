<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqvb-xbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqvb-xbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unarchive-fill" {...props}></Icon>
