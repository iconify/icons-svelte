<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygs_qq5iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygs_qq5iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:water-drop-slash" {...props}></Icon>
