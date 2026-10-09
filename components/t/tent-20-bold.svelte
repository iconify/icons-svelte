<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8gmoubzb.css';
import '../../css/o/oji4_ybzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g8gmoubzb"/><path class="oji4_ybzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tent-20-bold" {...props}></Icon>
