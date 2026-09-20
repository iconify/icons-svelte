<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycd0-xbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycd0-xbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:signal-circle-solid" {...props}></Icon>
