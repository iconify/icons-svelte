<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub--ebuyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub--ebuyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shirt-fill" {...props}></Icon>
