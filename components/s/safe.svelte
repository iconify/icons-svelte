<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7b948b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7b948b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:safe" {...props}></Icon>
