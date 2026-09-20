<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-kmasvkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-kmasvkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wechat-line" {...props}></Icon>
