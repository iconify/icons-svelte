<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve27pm75g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve27pm75g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trending-up-line" {...props}></Icon>
