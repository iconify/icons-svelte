<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xawi8xb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xawi8xb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rows-2" {...props}></Icon>
