<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx86lacyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx86lacyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:terminal-solid" {...props}></Icon>
