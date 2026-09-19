<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoxjkkblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoxjkkblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:time-five" {...props}></Icon>
