<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz1f_bc-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz1f_bc-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:swiper" {...props}></Icon>
