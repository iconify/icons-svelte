<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp44u9h7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp44u9h7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:twitter-fill" {...props}></Icon>
