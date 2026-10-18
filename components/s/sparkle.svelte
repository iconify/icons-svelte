<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xun-pbiej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xun-pbiej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sparkle" {...props}></Icon>
