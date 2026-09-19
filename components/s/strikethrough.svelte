<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyuq8031z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="iyuq8031z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:strikethrough" {...props}></Icon>
