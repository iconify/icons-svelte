<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szuftwbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szuftwbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:telegram" {...props}></Icon>
