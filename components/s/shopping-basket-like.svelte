<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ex4pjbc.css';
import '../../css/r/rvb6adcua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ex4pjbc"/><path class="rvb6adcua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:shopping-basket-like" {...props}></Icon>
