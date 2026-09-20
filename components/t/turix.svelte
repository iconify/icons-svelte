<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6_konbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6_konbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:turix" {...props}></Icon>
