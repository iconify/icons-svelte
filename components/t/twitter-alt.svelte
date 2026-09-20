<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu3rknbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu3rknbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:twitter-alt" {...props}></Icon>
