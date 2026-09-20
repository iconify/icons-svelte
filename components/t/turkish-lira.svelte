<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dryf0rbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dryf0rbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:turkish-lira" {...props}></Icon>
