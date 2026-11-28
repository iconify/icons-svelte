<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs4xh2bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4xh2bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:swap" {...props}></Icon>
