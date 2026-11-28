<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypnt1e9an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypnt1e9an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stove-clock" {...props}></Icon>
