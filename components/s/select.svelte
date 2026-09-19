<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_vvgb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":700};
const content = `<path class="k3_vvgb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:select" {...props}></Icon>
