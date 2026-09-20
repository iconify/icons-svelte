<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__wu0p8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k__wu0p8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:weight2" {...props}></Icon>
