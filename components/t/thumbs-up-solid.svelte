<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-g_vsbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-g_vsbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:thumbs-up-solid" {...props}></Icon>
