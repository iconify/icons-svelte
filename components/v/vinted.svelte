<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rylg1bu5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rylg1bu5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vinted" {...props}></Icon>
