<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8yjfcc4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8yjfcc4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tiktok-filled" {...props}></Icon>
