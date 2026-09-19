<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk6ttvbnd.css';
import '../../css/q/qx6xq3b3x.css';
import '../../css/p/pp6vxiujp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk6ttvbnd"/><path class="qx6xq3b3x"/><circle class="pp6vxiujp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-alert" {...props}></Icon>
