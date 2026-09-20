<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0azeacxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0azeacxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:voron-design" {...props}></Icon>
