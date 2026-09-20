<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yci7k2x8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="yci7k2x8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:set-square" {...props}></Icon>
