<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrw0g7hrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrw0g7hrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-shirt-air-fill" {...props}></Icon>
