<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj5y0bbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5y0bbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:window-alert" {...props}></Icon>
