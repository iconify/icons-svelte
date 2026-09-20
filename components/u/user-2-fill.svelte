<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hssap9bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hssap9bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-2-fill" {...props}></Icon>
