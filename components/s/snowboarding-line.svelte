<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr44mmb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr44mmb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowboarding-line" {...props}></Icon>
