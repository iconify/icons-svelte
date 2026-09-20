<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-sx8hbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-sx8hbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:taobao-fill" {...props}></Icon>
