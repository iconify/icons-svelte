<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlk091sld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk091sld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:twitter" {...props}></Icon>
