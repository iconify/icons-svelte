<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xja5e1bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xja5e1bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shutter" {...props}></Icon>
