<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7l5zccmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7l5zccmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zincsearch" {...props}></Icon>
