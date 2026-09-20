<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc3kirm1i.css';
import '../../css/n/n5821were.css';
import '../../css/z/zwvmvgb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pc3kirm1i"/><path class="n5821were"/><path class="zwvmvgb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:scroll-down" {...props}></Icon>
