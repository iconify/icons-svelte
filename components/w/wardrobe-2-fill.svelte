<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbtq6g3vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbtq6g3vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wardrobe-2-fill" {...props}></Icon>
